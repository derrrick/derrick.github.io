# Emergency Travel Brief

Your essential companion for informed and confident travel.

## About

The Emergency Travel Brief app provides travelers with a real-time overview of potential risks and essential readiness information before they travel. It combines weather data, visa requirements, and news on civil unrest into a concise, visual briefing.

## Features

- **Comprehensive Travel Brief:** Quickly view key information about your destination.
- **Live Weather Updates:** Integration with the OpenWeatherMap API to stay ahead of severe weather.
- **Instant News Feed:** Latest headlines that could impact travel using the GNews API.
- **Visa & Country Info:** Retrieve visa requirements via the REST Countries API.
- **Risk Readiness Score:** Visual risk and readiness scoring system.
- **User Authentication:** Secure registration and login.
- **Notifications:** Push notifications for critical alerts and updates.
- **Brief History:** Access previously generated briefs.

## Getting Started

1. Clone the repository.
2. Install dependencies with `npm install` inside the `app` folder.
3. Run the app with `npx react-native run-ios` or `npx react-native run-android`.

## APIs Used

- [OpenWeatherMap](https://openweathermap.org/api)
- [REST Countries](https://restcountries.com/)
- [GNews](https://gnews.io/)

## Development

The mobile application is built with React Native for cross-platform compatibility and is designed for deployment on AWS.

## Engineering MVP Development Plan

1. **Setup and Configuration** - Initialize React Native project and configure AWS services.
2. **User Authentication** - Secure user registration and login with encrypted credentials.
3. **API Integrations** - Connect to OpenWeatherMap, REST Countries, and GNews to collect destination data.
4. **Brief Generation** - Compile API data into a concise, visual travel brief with risk scoring.
5. **Notifications** - Implement push notification infrastructure for critical alerts.
6. **User Interface** - Develop intuitive UI components for inputting destinations and viewing briefs.
7. **Testing and Quality Assurance** - Unit, integration, and end-to-end tests to ensure performance and reliability.
8. **Deployment** - Deploy the application to AWS and release to iOS and Android stores.
9. **Monitoring and Feedback** - Monitor performance and collect user feedback for iterative improvements.

## Contact

For partnership inquiries, feedback, or support, please contact [support@emergencytravelbrief.com](mailto:support@emergencytravelbrief.com).

