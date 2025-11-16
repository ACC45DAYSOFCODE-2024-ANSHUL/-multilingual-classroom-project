🚀 Overview
> This project is an AI-powered multilingual classroom assistant designed to break language barriers in classrooms.
> Students can listen to lectures in any language, and the system instantly displays translated captions, real-time subtitles, and projector mode for classroom screens.
> You’ve built a beautifully designed mobile UI in HTML/CSS/JS that simulates real-time translation, live subtitles, Bluetooth connectivity, mic control, and projector mode.

🎯 Problem
> Students from different linguistic backgrounds struggle to understand teachers who speak in another language. Teachers can’t repeat everything in multiple languages, so students fall behind.

💡 Solution
Your app provides:
Real-time voice recognition
Automatic translation into 30+ languages
Live subtitle generation
Projector mode for classroom display
Bluetooth device support
Smooth UI with animations and interactive components
This makes classrooms inclusive and supports students who prefer learning in their mother tongue.

🌟 Key Features

🔊 Real-Time Voice Translation
The mic listens continuously and converts speech to translated subtitles.

🗣️ Live Subtitles Page
Shows original speech + translated text in a clean card UI.

🎥 Projector Mode
Dedicated large-screen subtitle box for classroom projectors
Big readable fonts
Dual captions
Auto-refresh animation
Live status indicator

🌍 Language Selector (30+ languages)
Supports almost all major Indian and international languages:
Hindi, English, Tamil, Telugu, Bengali, Marathi, Gujarati, Kannada, Punjabi, Malayalam, Urdu, Nepali, Sinhala, Chinese, Japanese, Korean, Arabic, French, German, Spanish, etc.

🎛 Bluetooth + Mic Controls
Toggle mic ON/OFF
Simulated Bluetooth connection animation

📱 App-Like UI (Mobile View)
Rounded phone frame
Navigation bar
Pages: Home / Start / Subtitles / About
Custom icons, glowing effects, animated buttons

🛠️ Tech Stack
Frontend & backend etc.
HTML
CSS (with gradients, animations, responsive layout)
JavaScript (Navigation + state + simulated voice translation)
AI Integration (Planned / For Prototype)
Google Gemini API (for real translation and speech processing)
Web Speech API (for voice recognition)
Other
Projector overlay mode using DOM manipulation
Toast notification system

📁 Folder Structure
/root
  └── multilingual_classroom_ui.html
  └── assets/ (optional if you add icons/videos)
  └── README.md

🧪 How to Run
Just open the HTML file:
index.html  (or the file you uploaded)
No installation needed.
Everything runs in the browser.

🔧 How to Add Real AI Translation (Future Work)
Replace the simulated translation function with a real API call:
const response = await fetch(
  "https://generativelanguage.googleapis.com/v1beta/models/gemini-pro:generateContent?key=API_KEY",
  {
    method: "POST",
    headers: { "Content-Type": "application/json" },
    body: JSON.stringify({
      contents: [{
        parts: [{ text: `Translate to ${targetLanguage}: ${text}` }]
      }]
    })
  }
);
This will make it a fully functional AI classroom assistant.

🎥 Demo Video
(You can add your YouTube link here later)

👥 Team Members

(Anshul Gole)

Himanshu Gour
Bulbul Goyal
kumari kajol
abhay sharma

🚀 Future Enhancements
Automatic language detection

Offline subtitle model
Teacher dashboard analytics
Student personalized learning summaries
Android/iOS app version 
