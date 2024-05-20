# Web-based Chat App

This is a simple chat application developed using ReactJS and Google Firebase. It includes the use of Firestore for database management and Firebase Auth for user authentication.

## Features

- User Authentication with Google Sign-In
- Real-time messaging with Firestore
- Simple User-friendly interface built with ReactJS

## Technologies Used

- ReactJS
- Firebase
  - Firestore
  - Firebase Auth

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:
```
git clone https://github.com/your-username/chat-app-firebase.git
cd chat-app-firebase
```
2. Install the dependencies:
```
npm install
```
3. Create a ```.env``` file in the root of the project and add your Firebase configuration details:
```
REACT_APP_API_KEY=your-api-key
REACT_APP_AUTH_DOMAIN=your-auth-domain
REACT_APP_PROJECT_ID=your-project-id
REACT_APP_STORAGE_BUCKET=your-storage-bucket
REACT_APP_MESSAGING_SENDER_ID=your-messaging-sender-id
REACT_APP_APP_ID=your-app-id
```
### Running the Application
1. Start the development server:
```
npm start
```
### Firebase Configuration
The Firebase configuration is stored in the .env file and loaded as environment variables in firebase.js. Ensure that the .env file is added to your .gitignore to keep your configuration details secure.

## Licence
This project is licensed under the MIT [License](https://github.com/MarshallOkafor/chat-app-firebase/blob/master/LICENSE).
