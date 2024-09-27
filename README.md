
# 💱 Currency Converter

A **Currency Converter** web application built using `HTML`, `CSS`, and `JavaScript`. The app fetches live exchange rates using an API and allows users to convert between different currencies in real time. 

## 🚀 Features

- 🌐 **Real-time currency conversion** using API data.
- 💰 **Supports multiple currencies** for conversion.
- 📊 **Responsive design** for an optimal user experience on any device.
- 🔄 **Instant results** upon selecting currencies and entering the amount.

## 📂 Project Structure

```bash
currency-converter/
├── index.html       # HTML structure for the Currency Converter
├── styles.css       # CSS for styling the app interface
└── script.js        # JavaScript logic for fetching data and performing conversion
```

## 🛠️ Technologies Used

- **HTML5**: For structuring the content and form elements.
- **CSS3**: For responsive design and styling the user interface.
- **JavaScript**: For fetching the latest exchange rates from the API and performing the currency conversion logic.

## 🔗 API Used

This project uses the **Exchange Rates API** (or any currency API of your choice) to fetch the latest currency conversion rates.

## ✨ How It Works

1. The user selects two currencies (from and to) and enters an amount.
2. Upon clicking the **"Convert"** button, JavaScript fetches the current exchange rate from the API.
3. The calculated result is displayed instantly based on the real-time data.

### Key Functionalities:

- **Currency Selection**: Dropdowns to select the base and target currencies.
- **Amount Input**: User inputs the amount to be converted.
- **Convert Button**: Triggers the API call to fetch exchange rates and perform the conversion.
- **Result Display**: The converted amount is displayed in real-time.

## 📋 Setup Instructions

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/sreenivasulareddyundela/currency-converter.git
   ```
2. Navigate to the project folder:
   ```bash
   cd currency-converter
   ```
3. Open the `index.html` file in your browser to view the app.

4. **Note**: You will need an API key to fetch live currency data. Sign up at [Exchange Rates API](https://exchangeratesapi.io/) or another similar service, and insert your API key in `script.js` at the appropriate place.

```js
const api = ` https://v6.exchangerate-api.com/v6/${apiKey}/latest/USD`;
let apiKey = "eb495535d773fd48436646c7"
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

🔗 **Live Demo**: [Currency Converter]((https://undelasreenivasulareddy.github.io/currency_Converter/)

💻 **Contributors**:  
- [Sreenivasulareddy Undela](https://github.com/sreenivasulareddyundela)

---

Made with ❤️ by [Sreenivasulareddy Undela](https://github.com/sreenivasulareddyundela)
