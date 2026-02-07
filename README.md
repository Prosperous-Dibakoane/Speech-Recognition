# Speech-Recognition

🎙️ Speech-to-Text Web Application

A simple, browser-based Speech-to-Text application built using HTML, CSS, and JavaScript, leveraging the Web Speech API to convert spoken words into written text in real time.

🚀 Features

🎧 Real-time speech recognition

📝 Converts voice input into text instantly

▶️ Start / ⏹️ Stop recording functionality

🌐 Runs directly in the browser (no backend required)

💡 Clean and responsive UI

🛠️ Technologies Used

HTML5 – Structure of the application

CSS3 – Styling and layout

JavaScript (ES6) – Application logic

Web Speech API – Speech recognition engine

📸 Preview

💡 Make sure the image is placed inside your repository and the path is correct.

📂 Project Structure
speech-to-text/
│
├── index.html        # Main HTML file
├── style.css         # Styling
├── script.js         # JavaScript logic
└── README.md         # Project documentation

⚙️ How It Works

The app uses the browser’s SpeechRecognition API.

When the user clicks Start, the microphone listens for speech.

Spoken words are transcribed and displayed as text.

Clicking Stop ends the recognition session.

⚠️ Best supported in Google Chrome and Chromium-based browsers.

▶️ Getting Started
1. Clone the Repository
git clone https://github.com/your-username/speech-to-text.git

2. Open the App

Simply open index.html in your browser.

cd speech-to-text
open index.html


No additional setup required ✅

🔐 Browser Permissions

Allow microphone access when prompted.

Ensure HTTPS is used if deployed online (required for microphone access).

🌍 Supported Browsers
Browser	Support
Chrome	✅ Yes
Edge	✅ Yes
Firefox	❌ Limited
Safari	⚠️ Partial
🚧 Limitations

Requires internet connection (depending on browser implementation)

Accuracy depends on microphone quality and environment

Language defaults to English (can be configured)

🧠 Future Improvements

🌍 Multi-language support

💾 Export transcriptions to file

🎨 Dark mode UI

📱 Mobile UI optimization

👤 Author

Prosperous Dibakoane
Software Engineering Student

📄 License

This project is open-source and available under the MIT License.
![Demo Screenshot](speech.png)

