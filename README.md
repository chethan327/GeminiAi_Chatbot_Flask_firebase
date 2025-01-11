# Gemini AI Chatbot

Gemini AI is an intelligent chatbot platform that leverages Firebase authentication and provides user login functionality along with chat history storage. This project is designed to be scalable, user-friendly, and easily extendable.

## Features

- **User Authentication**: Utilizes Firebase for secure user login and registration.
- **Chat History Storage**: Keeps track of user conversations for a personalized experience.
- **Integration with AI Models**: Supports Google Generative AI and other models for advanced chatbot interactions.
- **RESTful APIs**: Provides endpoints for user authentication, chat history retrieval, and more.
- **Scalable Backend**: Built with Flask and Firebase for robust performance.

## Prerequisites

1. **Python**: Ensure you have Python 3.7 or higher installed.
2. **Firebase Project**: Set up a Firebase project and download the service account key.
3. **Dependencies**: Install the required Python libraries listed in `requirements.txt`.

## Setup and Installation

1. **Clone the repository**:
https://github.com/chethan327/GeminiAi_Chatbot_Flask_firebase.git.
2. **Install dependencies**:
`pip install -r requirements.txt`.


3. **Configure Firebase**:
- Place the `serviceAccountKey.json` file in the root directory.
- Update `main.py` with your Firebase project details if necessary.

4. **Run the application**: `python main.py`

5. **Access the application**: Open your browser and navigate to http://127.0.0.1:5000/.

## Firebase Setup
1. Go to the Firebase Console.
2. Create a new project or select an existing one.
3. Navigate to Project Settings > Service Accounts, and generate a new private key.
4. Download the serviceAccountKey.json file and place it in the project root.

## Technologies Used
1. **Backend**: Flask, Firebase Admin SDK.
2. **AI Models**: Google Generative AI.
3. **Frontend**: HTML, CSS (in templates and static folders).

**Demo Video is Uploaded  with code**: https://github.com/chethan327/GeminiAi_Chatbot_Flask_firebase.git



