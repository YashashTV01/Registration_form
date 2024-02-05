# Registration Form

This is a simple HTML registration form. Users can input their personal information for account creation. Below is an explanation of the form components:

## Table of Contents
- [Overview](#overview)
- [Form Components](#form-components)
- [Usage](#usage)

## Overview
The registration form is designed to collect user data for account creation. It includes fields for the user's first name, last name, email, and a new password. Additionally, users can specify their account type (Personal or Business), upload a profile picture, input their age, specify how they heard about the service, and provide a bio.

The form also includes a checkbox for users to accept the terms and conditions.

## Form Components
### Personal Information
- **First Name**: `<input id="first-name" name="first-name" type="text" required />`
- **Last Name**: `<input id="last-name" name="last-name" type="text" required />`
- **Email**: `<input id="email" name="email" type="email" required />`
- **New Password**: `<input id="new-password" name="new-password" type="password" pattern="[a-z0-5]{8,}" required />`

### Account Type
- **Personal Account**: `<input id="personal-account" type="radio" name="account-type" class="inline" checked />`
- **Business Account**: `<input id="business-account" type="radio" name="account-type" class="inline" />`

### Additional Information
- **Profile Picture**: `<input id="profile-picture" type="file" name="file" />`
- **Age**: `<input id="age" type="number" name="age" min="13" max="120" />`
- **Referrer**: `<select id="referrer" name="referrer"> ... </select>`
- **Bio**: `<textarea id="bio" name="bio" rows="3" cols="30" placeholder="I like coding on the beach..."></textarea>`

### Terms and Conditions
- **Acceptance Checkbox**: `<input class="inline" id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" />`
- **Terms and Conditions Link**: `<a href="https://www.freecodecamp.org/news/terms-of-service/">terms and conditions</a>`

### Submission
- **Submit Button**: `<input type="submit" value="Submit" />`

## Usage
1. Open the HTML file in a web browser.
2. Fill in the required information in the form fields.
3. Select the account type (Personal or Business).
4. Upload a profile picture (optional).
5. Provide additional information such as age, referrer, and bio.
6. Accept the terms and conditions by checking the checkbox.
7. Click the "Submit" button to submit the form.
