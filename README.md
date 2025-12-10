# Driver-Drowsiness-Detection-System
A real-time computer vision system designed to improve road safety by detecting early signs of driver fatigue. By monitoring the driver’s eye movements using a webcam, the system alerts them with a sound alarm if drowsiness is detected, helping prevent accidents.

Features
- 🧠 Real-time facial landmark detection using dlib’s 68-point predictor  
- 👁️ Eye Aspect Ratio (EAR) calculation to detect prolonged eye closure  
- 🔊 Audible alarm triggered when drowsiness is detected  
- 🎥 Live webcam feed with visual indicators  
- ⚡ Lightweight and easy to run on most devices  
- 🛠️ Extendable for additional features like yawning detection or head pose analysis

🛠️ Technologies Used
> Python
> OpenCV
> dlib / Mediapipe (landmark detection)
> Numpy
> Pygame (for alert sound)

📸 How It Works
- Capture live video feed from webcam
- Detect face and extract facial landmarks
- Compute EAR & mouth ratio
- Identify drowsiness patterns
- Trigger warning when thresholds are exceeded

🚀 Applications
- Driver safety systems
- Fleet monitoring
- Automotive research
- Standalone fatigue detection applications

link to download dat file for detecting and extract facial landmarks:
https://drive.google.com/file/d/11ulB8EGlhcW3sLrVEBOcpdnNZaQrGILk/view?usp=sharing


detecting eye ratio live with using webcam

<img width="614" height="505" alt="image" src="https://github.com/user-attachments/assets/6feee3d8-c7f1-4a02-8f19-5b22efec250f" />

Trigger warning when thresholds are exceeded

<img width="677" height="552" alt="image" src="https://github.com/user-attachments/assets/6eb8ceb0-1974-48a6-9be6-a491a7d8cdd2" />





