# SensoVision

Sensovision



Sensovision is an AI-powered real-time emotion and face analysis system that detects human faces, analyzes emotions, and provides session-based statistics with export options.



🚀 Features



🎭 Emotion Detection – Recognizes multiple emotions like happy, sad, angry, fear, surprise, neutral, disgust.



🧑‍🤝‍🧑 Face Detection – Detects and highlights faces in live video streams or images.



👤 Person Detection – Identifies when no person is present in the frame.



📊 Session Analytics – Maintains a rolling average of detected emotions across a session.



⚡ Performance Metrics – Displays real-time latency and FPS (frames per second).



📥 Export Data – Save analysis results as JSON or CSV for further processing.



🖼️ Snapshot \& Auto Send – Capture annotated frames automatically or manually.



🎨 Custom Settings – Configure JPEG quality, image size, and UI theme toggle.



🖥️ User Interface



Left Panel: Displays the live video feed with bounding boxes and annotated labels (e.g., SAD, FEAR, NO PERSON DETECTED).



Right Panel:



Start/Stop controls



Mode selection (Default / Interview)



Detected emotions \& dominant state



Performance stats (Latency, FPS)



Rolling average emotions (session-wise)



Export options (Download JSON, Download CSV)



Snapshot \& Theme toggle



📌 Example Outputs



Detected Emotions:



sad: 48.8%, angry: 38.1%, neutral: 9.7%



Dominant emotion → Sad



Dominant Emotion:



fear: 99.04%



Rolling session averages for all emotions



No Person Detected:



Annotated bounding box with label → NO PERSON DETECTED



⚙️ Tech Stack



Frontend/UI: HTML5, CSS (Dark Theme), JavaScript



Backend: Python (Flask/FastAPI) running on localhost:5000



AI Models: Deep learning models for face detection \& emotion recognition



Libraries: OpenCV, TensorFlow/PyTorch, dlib/MTCNN (depending on implementation)



📂 Export Data



JSON: Raw structured output with probabilities for each emotion



CSV: Tabular data for offline analysis



🎯 Use Cases



Online interviews \& emotion tracking



Classroom/student attention analysis



Human-computer interaction research



Security \& surveillance monitoring

