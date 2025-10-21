# Captcha Solver

## Summary
A simple web application that displays a captcha image and simulates solving it within 15 seconds.

## Setup
1. Clone the repository.
2. Open `index.html` in a web browser.

## Usage
- Pass the captcha image URL as a query parameter in the URL (e.g., `?url=https://example.com/image.png`).
- If no URL is provided, a default sample captcha will be displayed.

## Code Explanation
- The app uses HTML and JavaScript to display the captcha image and simulate solving it.
- The `parseUrlParams` function retrieves the URL parameter for the captcha image.
- The captcha text is displayed after a 15-second delay.

## License
This project is licensed under the MIT License.

## Description
This app is designed to demonstrate a simple captcha display and solving simulation. It can be extended with actual captcha solving logic.