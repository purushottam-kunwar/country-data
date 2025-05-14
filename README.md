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
| country_name | string | Official country name |
| country_code | string (ISO2) | 2-letter country code |
| phone_code | string | International dialing code with + prefix |
| currency | string | Primary currency name |
| currency_code | string | 3-letter currency code |
| currency_symbol | string | Currency symbol |
| flag | string | Emoji flag or image path |

## Usage

### Direct JSON Access
```json
{
  "country_name": "United States",
  "country_code": "US",
  "phone_code": "+1",
  "currency": "Dollar",
  "currency_code": "USD",
  "currency_symbol": "$",
  "flag": "🇺🇸"
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
