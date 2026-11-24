# 🦖 Chrome Dino Autoplayer

An autonomous Dino Game controller built using **Python, OpenCV, Arduino and Servo Motor**.

### Overview
A computer vision-based automation system that detects obstacles in the Chrome Dino Game and triggers physical jumps through an Arduino-controlled servo motor.

### Key Features
- Light and dark theme detection
- Cactus and bird detection using OpenCV
- Real-time obstacle distance calculation
- Automated jump triggering
- Python-Arduino serial communication
- Servo-based physical jump mechanism

### Tech Stack
`Python` `OpenCV` `NumPy` `PyAutoGUI` `PySerial` `Arduino C++`

### Hardware
- Arduino board
- Servo motor
- USB connection

### Project Structure
```text
Dino-Game/
├── python/
│   └── main.py
├── arduino/
│   └── servo_control.ino
├── images/
├── requirements.txt
├── README.md
└── .gitignore
```

### Setup & Execution

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Upload the Arduino sketch.
3. Connect Arduino and configure the correct COM port in `main.py`.
4. Open Chrome Dino Game.
5. Run:
   ```bash
   python main.py
   ```

### Author
**Maitreyi** | Electrical Engineering Student