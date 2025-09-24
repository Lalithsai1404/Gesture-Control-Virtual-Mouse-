

# Gesture Controlled Virtual Mouse &nbsp;[![](https://img.shields.io/badge/python-3.8.5-blue.svg)](https://www.python.org/downloads/) [![platform](https://img.shields.io/badge/platform-windows-green.svg)](https://github.com/xenon-19/Gesture_Controller) 

Gesture Controlled Virtual Mouse makes human computer interaction simple by making use of Hand Gestures and Voice Commands. The computer requires almost no direct contact. All i/o operations can be virtually controlled by using static and dynamic hand gestures along with a voice assistant. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures and voice commands, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by [MediaPipe](https://github.com/google/mediapipe) running on top of pybind11. It consists of two modules: One which works direct on hands by making use of MediaPipe Hand detection, and other which makes use of Gloves of any uniform color. Currently it works on Windows platform.

 _Video Demonstration: [link](https://www.youtube.com/watch?v=ufm6tfgo-OA&ab_channel=Proton)_<br>
Note: Use Python version: 3.8.5

  Step 1: 
  ```bash
  conda create --name gest python=3.8.5
  ```
  
  Step 2:
  ```bash
  conda activate gest
  ```
  
  Step 3:
  ```bash
  pip install -r requirements.txt
  ```
  
  Step 4:
  ```bash 
  conda install PyAudio
  ```
  ```bash 
  conda install pywin32
  ```
  
  Step 5:
  ``` 
  cd to the GitHub Repo till src folder
  ```
  Command may look like: `cd C:\Users\.....\Gesture-Controlled-Virtual-Mouse\src`
  
  Step 6:
  
  For running Voice Assistant:
  ```bash 
  python Proton.py
  ```
  ( You can enable Gesture Recognition by using the command "Proton Launch Gesture Recognition" )
  
  Or to run only Gesture Recognition without the voice assisstant:
  
  Uncomment last 2 lines of Code in the file `Gesture_Controller.py`
  ```bash 
  python Gesture_Controller.py
  ```
  

  | Nishiket Bidawat | [Github](https://github.com/xenon-19) | [Email](mailto:bidawatnishiket@gmail.com) | [LinkedIn](https://www.linkedin.com/in/nishiket-bidawat-74b419193/) | [Instagram](https://myanimelist.net/profile/Xenon1901) |
  | Ankit Sharma | [GitHub](https://github.com/ankit-4129) | [Email](mailto:ankitsharma.rbt@gmail.com) | LinkedIn | Instagram |
  | Parth Sakariya | [Github](https://github.com/parth-12) | [Email](mailto:parthsakariya12@icloud.com) | [LinkedIn](https://www.linkedin.com/in/parth-sakariya-1886b2193/) | [Instagram](https://www.instagram.com/parth_sak12/) |
  
