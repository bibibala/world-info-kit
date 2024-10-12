# 🌍 world-info-kit

[![npm version](https://badge.fury.io/js/world-info-kit.svg)](https://badge.fury.io/js/world-info-kit)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**world-info-kit** is a comprehensive package containing key global data including languages, countries, timezones, currencies, and more. It is designed to provide easy access to essential information for applications that require international data.

## 🌟 Features

- **Languages**: Major languages of the world, including their English and Chinese names, along with corresponding flags.
- **Countries**: Country information including name, capital, region, subregion, and flag.
- **Timezones**: Timezones for each country, formatted as `UTC offset`.
- **Currency**: Currency details such as code, name, and symbol.
- **Start of the Week**: The start day of the week for each country.

## 📦 Installation

To install the package, run:

```bash
npm install world-info-kit
```

### Sample Output

```json
{
  "code": "eng",
  "name": "English",
  "flag": "https://flagcdn.com/gs.svg",
  "chinese": "英语",
  "capital": "King Edward Point",
  "region": "Antarctic",
  "subregion": "N/A",
  "timezones": [
    "UTC-02:00"
  ],
  "startOfWeek": "monday",
  "currency": {
    "code": "SHP",
    "name": "Saint Helena pound",
    "symbol": "£"
  }
}
```

## 🌍 Data Included

The package provides structured JSON data for easy access to global information. Here’s a breakdown of what’s included:

### 1. **Languages**

Each language entry includes:
- **code**: Language code (ISO 639-1 standard).
- **name**: The language’s name in English.
- **chinese**: The language’s name in Chinese.
- **flag**: URL of the corresponding country’s flag.

### 2. **Countries**

Each country entry includes:
- **code**: ISO Alpha-3 country code.
- **name**: The country's name in English.
- **capital**: The capital city.
- **region**: Geopolitical region (e.g., Africa, Europe).
- **subregion**: Sub-region, if applicable.
- **flag**: URL to the country's flag.

### 3. **Timezones**

- Timezones are listed per country and follow the `UTC±hh:mm` format.

### 4. **Currency**

Each currency entry contains:
- **code**: The official currency code (ISO 4217 standard).
- **name**: The full name of the currency.
- **symbol**: The symbol used for the currency (e.g., $, €, £).

### 5. **Start of the Week**

- Indicates whether the start of the week is Monday or Sunday for each country.

---

## 🌏 中文文档

[点击这里查看中文文档](#中文文档)

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/licenses/MIT) file for more details.
