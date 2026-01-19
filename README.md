# Lazy Dino Run - V0
This Web Application Game draws inspiration from the Chrome Dino Game which is an endless browser game that loads whenever the you are offline. This Projects mocks the same game logic, though instead of using keyboard keys to control your player, your camera captures eye movements as the alternative controls. 

## Features
- **AI Eye-Tracking Controls**: Uses MediaPipe to detect pupil movement and blinks to control the dinosaur.
- **Real-time Camera Feed**: Integrates with OpenCV.js to process webcam input in the browser.
- **Endless Runner Mechanics**: Features procedurally generated obstacles (cacti/birds) that increase in speed.
- **No-Install Playability**: Runs directly in standard desktop browsers via HTML5 Canvas and JavaScript. 

## Get Started
**Link to Browser:** https://dannyam2027.github.io/LazyDinoRun-V0/

**Instructions**:

**Allow Camera Access**: When prompted, allow the browser to use your webcam for eye tracking.

**Position Yourself**: Sit in a well-lit area so the camera can clearly detect your face and eyes.

**Gameplay Control**:
- Blink: Jump over obstacles.
- Tap/ Spacebar: Jump as well.

## Usage
- The game uses OpenCV.js for image processing to isolate facial features.
- It utilizes Mediapipe Face Mesh to track eye movements in real-time.
- The game logic is built with HTML5 Canvas and JavaScript.
- To run locally, open the index.html file in a modern browser (Chrome recommended) using a local server (e.g., Live Server in VS Code). 

## GamePlay
https://github.com/user-attachments/assets/fd9ef122-f89f-43a2-b4c3-30a1982932b1

