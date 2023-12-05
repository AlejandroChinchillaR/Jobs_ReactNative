# JobsReactNative

This project is a mobile application built using React Native, Expo, and Axios to allow users to search for various job listings, filter them by job type, view detailed job information, and apply to available job positions.

## Video
- [SearchJob - Video](https://github.com/AlejandroChinchillaR/Jobs_ReactNative/assets/104936330/c4ed616b-59ee-4027-8145-77cfa0bebfda)
- [ApplyJob - Video](https://github.com/AlejandroChinchillaR/Jobs_ReactNative/assets/104936330/7a3e15ff-ef6b-4a0f-85ca-ba36969ab972)
- [FilterJob - Video](https://github.com/AlejandroChinchillaR/Jobs_ReactNative/assets/104936330/190cfed0-6532-4700-bf97-0c3a3f40b62e)


## Features

- **Search Jobs**: Users can search for job listings based on keywords and view a list of available jobs.
- **Filter by Job Type**: Filtering options available to narrow down job listings based on job types or categories.
- **Job Details**: Detailed information provided for each job listing, including job description, requirements, and location.
- **Apply to Jobs**: Users can apply to job listings by being redirected to the job website.





## Prerequisites

- Node.js (version 16.0 or higher) installed
- Expo CLI (version 49.0.3) installed globally (`npm install -g expo-cli`)
- Yarn or npm package manager

## Getting Started

1. Clone this repository:

    ```bash
    git clone git@github.com:AlejandroChinchillaR/Jobs_ReactNative.git
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
