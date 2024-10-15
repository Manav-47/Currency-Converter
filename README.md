# Currency Converter App

This is a simple, web-based **Currency Converter App** that allows users to quickly convert values between different currencies using real-time exchange rates. The app leverages the **ExchangeRate-API** to fetch live exchange rates and provides a user-friendly interface for selecting currencies and viewing conversion results.

## Features:
- **Live Exchange Rates**: Uses the latest exchange rates provided by the ExchangeRate-API.
- **Currency Selection**: Dropdown menus to select the base currency and target currency.
- **Real-Time Calculation**: Automatically calculates and displays the conversion result upon user input.
- **Country Flags**: Displays the corresponding country flags based on the selected currency.
- **Default Selections**: Pre-selects commonly used currencies (USD to INR) for convenience.
- **Error Handling**: Provides clear error messages when data is unavailable or inputs are invalid.

## Technologies:
- **HTML/CSS/JavaScript**: The app is built using standard front-end technologies to ensure simplicity and wide browser compatibility.
- **ExchangeRate-API**: For fetching real-time exchange rates.
- **Flags API**: Used to dynamically display country flags based on selected currency.

## Setup:
1. Clone this repository:
   ```
   git clone https://github.com/yourusername/currency-converter.git
   ```
2. Open the `index.html` file in your browser.
3. (Optional) To deploy the project, upload it to a web server or hosting platform like GitHub Pages.

## How to Use:
1. Enter the amount you want to convert.
2. Select the base currency (e.g., USD).
3. Select the target currency (e.g., INR).
4. Click **Convert** to see the conversion result.
   
## API Documentation:
The app integrates with the [ExchangeRate-API](https://www.exchangerate-api.com/docs) for real-time data and uses country flags from a flag API to enhance the user interface.

