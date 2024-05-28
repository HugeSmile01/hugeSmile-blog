# HugeSmile

HugeSmile is an Android application for my blog. It features a maintenance screen, flash screen, update screen, and the ability to send notifications through an admin panel. The app uses Firebase as the backend, utilizing Firebase Realtime Database to store and retrieve data for a customizable blogging experience. Note that the admin panel is a separate application located in a different repository.

## Features

- **Maintenance Screen**: Displays a maintenance message when the app is under maintenance.
- **Flash Screen**: Displays a flash screen upon startup.
- **Update Screen**: Notifies users about app updates.
- **Notifications**: Sends notifications to users, managed through a separate admin panel application.
- **Firebase Integration**: Uses Firebase Realtime Database for data storage and retrieval.

## Getting Started

### Prerequisites

- Android Studio
- Firebase account

### Installing

1. **Clone the repository:**

   ```sh
   git clone https://github.com/HugeSmile01/hugeSmile-blog.git
   cd hugeSmile-blog
   ```

2. **Open the project in Android Studio.**

3. **Set up Firebase:**
   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Create a new project or use an existing one.
   - Add an Android app to your Firebase project.
   - Follow the steps to download the `google-services.json` file.
   - Place the `google-services.json` file in the `app` directory of your Android project.
   - Enable Firebase Realtime Database and set up your database rules.

4. **Build and run the app:**
   - Connect your Android device or use an emulator.
   - Click the "Run" button in Android Studio.

## Admin Panel

The admin panel for managing notifications and app updates is located in a separate repository. You can find it [here](https://github.com/HugeSmile01/hugesmile-admin-panel).

## Usage

- The maintenance, flash, and update screens can be customized through the Firebase Realtime Database.
- Notifications can be sent through the admin panel.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/yourFeatureName`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/yourFeatureName`).
5. Create a new Pull Request.

## Acknowledgments

- [Firebase](https://firebase.google.com/)
- [Android Studio](https://developer.android.com/studio)
