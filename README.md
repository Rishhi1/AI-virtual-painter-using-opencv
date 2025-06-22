🖌️PaintAI – Voice & Gesture Controlled Virtual Painter
PaintAI is an intelligent, real-time virtual painting application that combines hand gesture recognition with a voice-controlled assistant named Jarvis. Designed using OpenCV, MediaPipe, and Python's speech libraries, PaintAI lets users draw, erase, and switch tools or colors effortlessly using natural hand gestures or simple spoken commands.

✨ Unique Features
🎙️ AI Voice Assistant (Jarvis)
Wake word activation: "Jarvis"

Understands commands like:

Jarvis clear – Clears the canvas

Jarvis red / blue / green / black – Changes drawing color

Jarvis eraser, rectangle, circle, line, draw – Switches tools

Jarvis help – Lists available voice commands

Jarvis quit – Exits the app

Real-time speech recognition via Google and text-to-speech feedback with pyttsx3

Runs in a dedicated background thread, allowing seamless multitasking

✋ Gesture-Based Drawing
Powered by MediaPipe hand tracking

Recognizes hand gestures to:

Draw with index finger

Switch tools using two-finger tap gestures

Use pinch gesture to draw shapes (rectangle, circle, line)

Clear the canvas with an intuitive "open-then-close palm" motion

🧠 Intelligent Interaction
Combines voice commands and gestures to offer a fluid and natural drawing experience

Includes debouncing and gesture smoothing to prevent accidental inputs

Dynamically updates UI elements to reflect tool changes in real-time

🛠️ Tech Stack
Python 3

OpenCV – Image processing & drawing

MediaPipe – Hand gesture recognition

SpeechRecognition – Voice input

pyttsx3 – Text-to-speech

NumPy – Matrix operations

🚀 How to Run
Install dependencies:

bash
Copy
Edit
pip install opencv-python mediapipe speechrecognition pyttsx3 numpy
Run the application:

bash
Copy
Edit
python paintAI.py
Use your hand gestures or say commands starting with "Jarvis" to control the app.

🧩 Voice Commands Reference
Command	Action
Jarvis clear	Clears the canvas
Jarvis red	Switch to red color
Jarvis green	Switch to green
Jarvis blue	Switch to blue
Jarvis black	Switch to black
Jarvis eraser	Select eraser tool
Jarvis rectangle	Draw rectangles
Jarvis circle	Draw circles
Jarvis line	Draw straight lines
Jarvis draw	Freehand drawing
Jarvis help	List available commands
Jarvis quit	Exit the app

🤖 Why PaintAI is Different
Unlike traditional paint applications, PaintAI enables contactless interaction, making it perfect for touchless environments, educational demos, or creative experimentation. Its multi-modal input system (voice + gestures) is not only intuitive but also inclusive for users who may prefer voice or motion over physical input devices.

📷 Preview (Optional)
Include GIFs or screenshots here of:

Gesture drawing

Voice command interaction

Dynamic tool switching

📄 License
MIT License. Use and modify freely for learning or enhancement.

