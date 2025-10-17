# Temperature Converter

## Summary
This is a simple, single-page web application that allows users to convert temperatures between Celsius and Fahrenheit. Users can input a temperature value into either field, and the application will automatically display the equivalent temperature in the other unit. The conversion works bidirectionally, providing real-time, synchronized updates for an intuitive experience.

## Setup
This project is a static HTML file. To run the application:
1. Download or clone the repository.
2. Open the `index.html` file in your preferred web browser.
3. Enter a temperature value in either the Celsius or Fahrenheit input field to see the conversion happen instantly.

## Code Explanation
The application is built using plain HTML, CSS, and JavaScript:
- The HTML creates the structure with two labeled input fields for Celsius and Fahrenheit.
- The CSS styles the page for a clean, centered appearance with responsive design considerations.
- The JavaScript adds event listeners to the input fields:
  - When the user types in Celsius, the script calculates and displays the equivalent Fahrenheit value.
  - Conversely, inputting in Fahrenheit updates the Celsius value.
  - An `isUpdating` flag prevents infinite loops caused by the input fields updating each other.
- The `parseNumber` function ensures only valid numeric values are processed, clearing the other field if input is invalid.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.