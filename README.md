
# Nature Nest 🌍

**Nature Nest** is a mobile application designed to educate and engage users about climate change in a fun and interactive way. Our app offers quizzes, real-time weather updates, and AI-powered waste classification to encourage eco-friendly habits, all in one convenient place.

## Key Features 🌟

- **Secure Login & Registration**:  
  User data is protected with a secure login system.
  
- **Interactive Quizzes**:  
  Test your knowledge on climate change through engaging quizzes with achievements.
  
- **Real-Time Climate Status**:  
  Stay updated with real-time weather and temperature data.
  
- **Recyclable Object Classification**:  
  An AI-powered feature that helps users identify recyclable objects to improve waste management.
  
- **Eco-Friendly Chatbot**:  
  Ask questions about climate change and get eco-friendly tips from a smart chatbot.

## Installation 🔧

To get the app running locally, follow the steps below.

### Prerequisites 📋

- **Node.js** installed on your machine. Download Node.js [here](https://nodejs.org/).
- **VS Code** or another code editor is recommended. Download VS Code [here](https://code.visualstudio.com/).
- **EXPO GO** app installed on your mobile device (Available on [Google Play Store](https://play.google.com/store/apps) and [Apple App Store](https://apps.apple.com/app/expo-go/id982107779)).

### Setup Instructions

#### 1. Clone the repository

Run the following command in your terminal:

```bash
git clone <repository-url>
```

#### 2. Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Install dependencies and start the server:

```bash
npm install
npm start
```

#### 3. Configure IP Address

After starting the backend, copy your local IP address from the terminal.

- Navigate to the root directory and open the `.env` file.
- Paste your IP address into the `.env` file like so:

```bash
API_URL=http://<your_ip>:<port>
```

#### 4. Frontend Setup

Navigate back to the root directory:

```bash
cd ../
```

Install dependencies and start the frontend:

```bash
npm install
npm start
```

### Running the App on Your Mobile Device

1. Open the **EXPO GO** app on your mobile device.
2. Scan the QR code generated in your terminal with the **EXPO GO** scanner.

You're all set! 🎉  
The app will load on your device, and you can explore **Nature Nest**!

## Tech Stack 🛠️

- **Frontend**: React Native
- **Backend**: Express.js, Node.js
- **Database**: MongoDB
- **APIs**: Gemini Vertex API, Axios
- **Real-Time Communication**: Socket.io

## Future Plans 🚀

- **More Quizzes**:  
  Expanding the quiz section with additional content and fun facts.

- **Community Features**:  
  Creating a platform for users to share eco-friendly ideas and tips.

- **Personalized Recommendations**:  
  Using AI to offer tailored eco-friendly tips based on user activities.

- **Global Expansion**:  
  Adding support for multiple languages to reach users across the world.

## Contributing 🤝

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add some feature"
   ```

4. Push the branch to your fork:

   ```bash
   git push origin feature-name
   ```

5. Open a Pull Request.

## License 📄

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact ✉️

If you have any questions or feedback, feel free to reach out.

Thank you for using and contributing to **Nature Nest**! 🌿🌎

