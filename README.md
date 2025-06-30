# ✋ Hand Scanner using OpenCV and MediaPipe
A real-time hand scanning simulation project built with OpenCV, MediaPipe, and Python. It overlays a hand template image on the webcam feed and detects when a real hand aligns perfectly inside the template. Once aligned, a custom video (vid.mp4) is played — simulating a biometric scanner.

# 🚀 Features
🖐️ Real-time hand detection using MediaPipe Hands
🎯 Scanning area overlay with a transparent hand template
📹 Plays a custom video when a hand is aligned properly
🔍 Bounding box check to verify full hand is inside template
✅ Custom overlay with alpha blending for realistic visual effect

# 🛠️ Technologies Used
OpenCV – for webcam access, frame rendering, and video playback
MediaPipe – for accurate hand landmark detection
Python – core language

📁 Project Structure

Hand-Scanner/
├── main.py              
├── hand_template.png      
├── vid.mp4 

# 🔧 How It Works

The webcam feed is opened and mirrored like a mirror.
A transparent hand scan overlay is displayed at the center.
MediaPipe detects hand landmarks in real time.
If a hand is aligned completely inside the overlay area:
The scanner plays a video (vid.mp4) as feedback.
After the scan, the system resets to allow repeated scans.
