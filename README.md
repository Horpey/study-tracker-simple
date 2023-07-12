# Study Tracker

Study Tracker is a web application that allows students to track their study progress. It provides features to log study sessions, record subjects, study time, notes, and more.

## Getting Started

To get started with Study Tracker, follow the steps below:

1. Clone the repository:
   git clone https://github.com/Horpey/study-tracker-simple.git

2. Navigate to the project directory:
   cd study-tracker

3. Rename the `config.js.template` file:
   cp config.js.template config.js

4. Update the configuration values:

Open the `config.js` file and update the placeholder values with your actual Firebase configuration details. Replace `YOUR_API_KEY`, `YOUR_AUTH_DOMAIN`, `YOUR_DATABASE_URL`, `YOUR_PROJECT_ID`, `YOUR_STORAGE_BUCKET`, `YOUR_MESSAGING_SENDER_ID`, and `YOUR_APP_ID` with the corresponding values from your Firebase project.

```javascript
var firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  databaseURL: "YOUR_DATABASE_URL",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};

Start the application:

Open the index.html file in a web browser or set up a local server to serve the files.

Begin using Study Tracker:

You can now start using Study Tracker to track your study sessions and monitor your progress.

Contributing
Contributions to Study Tracker are welcome! If you find any issues or have suggestions for improvements, feel free to submit a pull request or open an issue in the repository.

```
