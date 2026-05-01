# DailyBites.Recipes

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

The core recipe service for **DailyBites**, an intelligent daily recipe suggestion platform that personalizes recommendations based on user preferences and dietary requirements.

## Overview

DailyBites.Recipes is a microservice designed to generate and manage personalized daily recipe suggestions. It leverages AI-powered recommendations and intelligent data management to provide users with tailored cooking and ordering options.

## Key Features

- **AI-Powered Recommendations**: Integrates with OpenAI API to generate personalized recipe suggestions
- **Multi-Language Support**: Supports recipe generation in multiple languages
- **Flexible Preferences**: Accommodates cooking or food ordering preferences
- **Smart Deduplication**: Utilizes unique keys to prevent duplicate recipes in the database
- **Recipe History**: Maintains a 30-day recipe history for each user
- **Efficient Data Storage**: SQL-based persistence with optimized queries
- **Easy Access & Refresh**: Users can easily retrieve or refresh their recipe history

## How It Works

1. **User Input**: Users specify their language preference and select cooking or ordering as their preferred method
2. **AI Generation**: The service queries OpenAI API to generate relevant recipe suggestions
3. **Data Persistence**: Recipes are stored in a SQL database with unique identifiers to ensure no duplicates
4. **History Management**: Users can access or refresh recipes from their past 30 days of history
5. **Personalization**: Recommendations are tailored based on user preferences and patterns

## Technology Stack

- **API Integration**: OpenAI API for intelligent recipe generation
- **Database**: SQL for reliable data storage and retrieval
- **Language**: C#
- **Framework**: .NET 10

## Getting Started

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## Support

For issues, questions, or suggestions, please [create an issue](../../issues) in this repository.

## License

DailyBite is licensed under the MIT License. See [LICENSE](https://github.com/DailyBites-System/DailyBite/blob/main/LICENSE) for more information.


## Related Services

- [DailyBites.Users](https://github.com/DailyBites-System/DailyBites.Users) - User management service
- [DailyBites.API](https://github.com/DailyBites-System/DailyBites.API) - Main API gateway


## Contact

For questions or feedback, please contact Ahmed Hussain aka huzcodes at huzcodes@outlook.com.

---

**Part of the DailyBites Ecosystem** | [Main Repository](https://github.com/DailyBites-System)
