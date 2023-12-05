# JobsReactNative

This project is a mobile application built using React Native, Expo, and Axios to consume an API for displaying job listings.

## Prerequisites

- Node.js (version 16.0 or higher) installed
- Expo CLI (version 49.0.3) installed globally (`npm install -g expo-cli`)
- Yarn or npm package manager

## Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/JobsReactNative.git
    cd JobsReactNative
    ```

2. Install dependencies:

    ```bash
    npm install
    # or
    yarn install
    ```

3. Start the development server:

    ```bash
    expo start
    ```

4. Open the Expo Go app on your iOS or Android device. Scan the QR code displayed in the terminal or in the Expo Dev Tools that opened in your browser.

5. Explore the app on your device.

## Project Structure

- `App.js`: Entry point of the application.
- `app/`: Contains screens of the application.
  - `job-details/`: Screen displaying job details.
  - `search/`: Screen for searching job listings.
- `hooks/`: Contains custom hooks.
  - `useFetch.js`: Hook for making API calls using Axios.

## Libraries and Technologies Used

- Expo (version 49.0.3): Provides a set of tools and services for building React Native applications.
- React Native (version 0.72.6): A framework for building native mobile apps using React.
- Axios: A promise-based HTTP client for making API requests.
- Node.js (version 16.0 or higher): JavaScript runtime environment.
- JSX: A syntax extension for JavaScript used with React to describe UI components.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the application, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
