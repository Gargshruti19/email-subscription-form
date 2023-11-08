
# Email Subscription Form

This repository contains a simple HTML and JavaScript code for creating an email subscription form. Users can subscribe to receive updates about an upcoming website. The form data is submitted to a Google Sheets document via a Google Apps Script, allowing you to collect user email addresses for future communication.

## How It Works

- The HTML structure is defined within the `index.html` file. It consists of the following components:
  - A hero section with a background image and subscription form.
  - Input field for users to enter their email address.
  - A "Subscribe" button to submit the email address.
  - A message area to display feedback to the user.

- JavaScript is used to add functionality to the form. When a user submits their email address, the form data is sent to a Google Apps Script using the Fetch API.

- The Google Apps Script URL (`scriptURL`) is specified in the JavaScript. You should replace this URL with your own script URL for data submission.

- When the form is submitted, the script sends a POST request with the form data to the Google Apps Script. If the submission is successful, a "Thank you for subscribing!" message is displayed for 5 seconds, and the form is reset.

## Styling

The CSS for styling the page is defined in an external stylesheet (`style.css`). It sets the background, font, and layout for the hero section and form.

## Usage

1. Fork or clone this repository to your local machine.
2. Replace the `scriptURL` in the JavaScript with the URL of your own Google Apps Script.
3. Customize the background image, text, and styling in the HTML and CSS to fit your needs.
4. Host the HTML and CSS files on a web server or platform of your choice.
5. Deploy your Google Apps Script to handle form submissions.
6. Update the URL in your Google Apps Script with the published URL.
7. Publish your website with the subscription form.

## License

This code is provided under an open-source license. Feel free to modify and use it for your projects.

---

Enjoy using this email subscription form to gather subscribers for your upcoming website!
