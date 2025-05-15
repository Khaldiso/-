# Fuel Consumption Calculator

This project is a web-based application designed to calculate fuel consumption in a factory setting. Users can input invoice data for various fuel types and units, and the application will perform the necessary calculations based on the provided data.

## Features

- Input for multiple fuel types: Diesel, Gasoline, LPG, NG, Light Fuel Oil, Heavy Fuel Oil, Base Oil, Used Oil.
- Support for various units: Liter, Tonne, BTU, etc.
- Option to select working days: 5 days or 7 days per week.
- User-friendly interface for easy data entry and calculation.

## Project Structure

```
fuel-consumption-calculator
├── src
│   ├── index.html          # Main HTML document
│   ├── styles
│   │   └── main.css       # CSS styles for the application
│   ├── scripts
│   │   ├── app.js         # Main JavaScript file for application logic
│   │   └── utils.js       # Utility functions for calculations and validations
│   └── components
│       ├── CalculatorForm.js  # Form for user input
│       ├── FuelTypeSelector.js # Component for selecting fuel type
│       └── UnitConverter.js    # Component for unit conversion
├── package.json           # npm configuration file
└── README.md              # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd fuel-consumption-calculator
   ```

3. Install the dependencies:
   ```
   npm install
   ```

## Usage

1. Open `src/index.html` in your web browser.
2. Fill in the invoice data in the provided form.
3. Select the fuel type and unit of measurement.
4. Choose the number of working days.
5. Click on the calculate button to see the results.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.