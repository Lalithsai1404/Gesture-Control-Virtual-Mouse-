


A Human-Computer Interaction project that allows users to control their system using hand gestures and voice commands instead of traditional input devices. The solution leverages Computer Vision and Machine Learning with MediaPipe (CNN-based) for gesture recognition and a lightweight voice assistant for commands. It supports operations like cursor movement, clicking, scrolling, drag-and-drop, and even controlling system volume/brightness — all without additional hardware. Built for Windows with Python 3.8.5.

Environment Setup
Create a virtual environment:

bash
Copy code
conda create -n gest python=3.8.5
Activate the environment:

bash
Copy code
conda activate gest
Install project dependencies:

bash
Copy code
pip install -r requirements.txt
Install required libraries for audio and system-level access:

bash
Copy code
conda install PyAudio  
conda install pywin32
Navigate to the source directory (example):

bash
Copy code
cd C:\Users\...\Gesture-Controlled-Virtual-Mouse\src
Run the application:

To start with voice assistant:

bash
Copy code
python Proton.py
To directly launch gesture recognition, use the command:

bash
Copy code
"Proton Launch Gesture Recognition"
  
  Uncomment last 2 lines of Code in the file `Gesture_Controller.py`
  ```bash 
  python Gesture_Controller.py
  ```
  
