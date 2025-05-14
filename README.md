# Country Data Repository

🌍 A comprehensive dataset of country information including names, codes, currencies, and flags.

## Dataset Contents

- **250+ countries** with standardized information
- **Currency details** with codes and symbols
- **Phone codes** with + prefix
- **Flag representations** (emoji or paths)

## Data Fields

| Field | Type | Description |
|-------|------|-------------|
| Country Name | string | Official country name |
| Country Code | string (ISO2) | 2-letter country code |
| Phone Code | string | International dialing code with + prefix |
| Currency | string | Primary currency name |
| Currency Code | string | 3-letter currency code |
| Currency Symbol | string | Currency symbol |
| Flag | string | Emoji flag or image path |

## Usage

### Direct JSON Access
```json
{
  "Country Name": "United States",
  "Country Code": "US",
  "Phone Code": "+1",
  "Currency": "Dollar",
  "Currency Code": "USD",
  "Currency Symbol": "$",
  "Flag": "🇺🇸"
}
```

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/country-data.git
```

2. Use in your project:
```javascript
const countries = require('./country-data/data/merged_countries.json');
```

## Data Sources
- Primary data from [REST Countries API](https://restcountries.com)
- Enhanced with currency/phone code data from [GeoNames](https://www.geonames.org)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Please open an issue to:
- Report data inaccuracies
- Suggest additional fields
- Propose format improvements
```
