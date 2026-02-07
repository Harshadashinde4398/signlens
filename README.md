# signlens
SignLens - AI-Based Sign Language Interpreter
A real-time web application that interprets sign language gestures using computer vision and machine learning (MediaPipe). Designed for accessibility and inclusive education.

🚀 Live Demo
**Click here to view the live project**

✨ Features
Real-Time Hand Tracking: Uses MediaPipe Hands for high-performance hand landmark detection.
Multi-Gesture Recognition: Supports single-hand and two-hand gestures.
Responsive Design: Works on desktop and mobile browsers.
Privacy-Focused: All processing happens locally in the browser; video data is never sent to a server.
Speech-to-Text: Integrated speech recognition for two-way communication.
👐 Supported Gestures
See the full Gesture Guide for detailed instructions.

Basic Numbers
0 - 5 (Single hand)
6 - 10 (Two hands)
Common Phrases
Yes / No
Thumbs Up / Down
Okay
Thank You
Call Me / I Love You
Hello / Bye
Help / Stop
And more...
🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (Vanilla)
AI/ML: MediaPipe Hands (Google), Custom Geometric Classifiers
Deployment: GitHub Pages

📂 Project Structure
D:\hacknova\SignLens\
├───frontend\           # Main application code
│   ├───index.html      # (Old UI restored in root for live site)
│   ├───style.css       # New styling (optional)
│   ├───old-style.css   # Original styling (active)
│   ├───gesture.md      # Guide to gestures
│   └───src\
│       ├───app.js      # Main logic
│       └───gesture-detection.js # Gesture recognition engine
├───backend\            # (Optional backend components)
└───...

👨‍💻 Development
Setup
Clone the repository:
git clone https://github.com/Harshadashinde4398/Sign-Language-Interpreter.git

Navigate to the project directory:
cd Sign-Language-Interpreter
Open index.html in your browser to test locally.
Contributing
Pull latest changes: git pull origin main
Make your changes.
Stage changes: git add .
Commit: git commit -m "Description of changes"
Push: git push origin main
Part of HackNova Hackathon Project - Team SignLens
