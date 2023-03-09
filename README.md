# COMPUTER SIMULATED VIRTUAL HAND MOTION DETECTING CURSOR WITH VOICE ASSISTANCE &nbsp;[![](https://img.shields.io/badge/python-3.8.5-blue.svg)](https://www.python.org/downloads/) [![platform](https://img.shields.io/badge/platform-windows-green.svg)](https://github.com/xenon-19/Gesture_Controller) 
MADE BY : VAISAKH SRIRAM

Gesture Controlled Virtual Mouse makes human computer interaction simple by making use of Hand Gestures and Voice Commands. The computer requires almost no direct contact. All i/o operations can be virtually controlled by using static and dynamic hand gestures along with a voice assistant. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures and voice commands, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by [MediaPipe](https://github.com/google/mediapipe) running on top of pybind11. It consists of two modules: One which works direct on hands by making use of MediaPipe Hand detection, and other which makes use of Gloves of any uniform color. Currently it works on Windows platform.

Note: Use Python version: 3.8.5

# Features
 _click on dropdown to know more_ <br>

### Gesture Recognition:
<details>
<summary>Neutral Gesture</summary>
 <figure>
  <img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Palm" width="711" height="400"><br>
  <figcaption>Neutral Gesture. Used to halt/stop execution of current gesture.</figcaption>
</figure>
</details>
 

<details>
<summary>Move Cursor</summary>
  <img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Move Cursor" width="711" height="400"><br>
  <figcaption>Cursor is assigned to the midpoint of index and middle fingertips. This gesture moves the cursor to the desired location. Speed of the cursor movement is proportional to the speed of hand.</figcaption>
</details>

<details>
<summary>Left Click</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Left Click" width="711" height="400"><br>
 <figcaption>Gesture for single left click</figcaption>
</details>

<details>
<summary>Right Click</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Right Click" width="711" height="400"><br>
 <figcaption>Gesture for single right click</figcaption>
</details>

<details>
<summary>Double Click</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Double Click" width="711" height="400"><br>
 <figcaption>Gesture for double click</figcaption>
</details>

<details>
<summary>Scrolling</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Scrolling" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for horizontal and vertical scroll. The speed of scroll is proportional to the distance moved by pinch gesture from start point. Vertical and Horizontal scrolls are controlled by vertical and horizontal pinch movements respectively.</figcaption>
</details>

<details>
<summary>Drag and Drop</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Drag and Drop" width="711" height="400"><br>
 <figcaption>Gesture for drag and drop functionality. Can be used to move/tranfer files from one directory to other.</figcaption>
</details>

<details>
<summary>Multiple Item Selection</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Multiple Item Selection" width="711" height="400"><br>
 <figcaption>Gesture to select multiple items</figcaption>
</details>

<details>
<summary>Volume Control</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Volume Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Volume control. The rate of increase/decrease of volume is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

<details>
<summary>Brightness Control</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="Brightness Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Brightness control. The rate of increase/decrease of brightness is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

### Voice Assistant ( ***PROTON*** ):
<details>
<summary>Launch / Stop  Gesture Recognition</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="launch stop gesture recognition" width="250" height="auto">
<ul>
  <li>
    <code> Proton Launch Gesture Recognition </code><br>
    Turns on webcam for hand gesture recognition.
  </li>
  <li>
    <code> Proton Stop Gesture Recognition </code><br>
    Turns off webcam and stops gesture recognition.
    (Termination of Gesture controller can also be done via pressing <code>Enter</code> key in webcam window)
   </li>
</ul>
</details>

<details>
<summary>Google Search</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton search github" width="800" height="auto">
<ul>
  <li>
    <code>Proton search {text_you_wish_to_search}</code><br>
    Opens a new tab on Chrome Browser if it is running, else opens a new window. Searches the given text on Google.
  </li>
</ul>
</details>

<details>
<summary>Find a Location on Google Maps</summary>
 <img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton find location" width="800" height="auto">
  <ol>
    <li> 
      <code>Proton Find a Location</code><br>
      Will ask the user for the location to be searched.
    </li>
    <li> 
      <code>{Location_you_wish_to_find}</code><br>
      Will find the required location on Google Maps in a new Chrome tab.
    </li>
  </ol>
</details>

<details>
<summary>File Navigation</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton list files" width="250" height="auto">&emsp;
 <img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton open" width="250" height="auto">&emsp;
 <img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton go back" width="250" height="auto">
  <ul>
    <li>
      <code>Proton list files</code> / <code> Proton list </code><br>
      Will list the files and respective file_numbers in your Current Directory (by default C:)
    </li>
    <li>  
      <code> Proton open {file_number} </code><br>
      Opens the file / directory corresponding to specified file_number.
    </li>
    <li>
      <code>Proton go back </code> / <code> Proton back </code><br>
      Changes the Current Directory to Parent Directory and lists the files.
    </li>
  </ul>
</details>

<details>
<summary>Current Date and Time</summary>
<img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton date / time" width="250" height="auto">
  <ul>
    <li>
      <code> Proton what is today's date </code> / <code> Proton date </code><br>
      <code> Proton what is the time </code> / <code> Proton time </code><br>
      Returns the current date and time.
    </li>
  </ul>
</details>

<details>
<summary>Copy and Paste</summary>
 <img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton copy" width="500" height="auto">
 <img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton paste" width="500" height="auto">
  <ul>
    <li>
      <code> Proton Copy </code><br>
      Copies the selected text to clipboard.<br>
    </li>
    <li>
      <code> Proton Paste </code><br>
      Pastes the copied text.
    </li>
  </ul>
</details>

<details>
<summary>Sleep / Wake up Proton</summary>
  <img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton sleep / wake up" width="250" height="auto">
  <ul>
    <li>
      Sleep<br>
      <code> Proton bye </code><br>
      Pauses voice command execution till the assistant is woken up.
    </li>
    <li>
      Wake up<br>
      <code> Proton wake up </code><br>
      Resumes voice command execution.
    </li>
  </ul>
</details>

<details>
<summary>Exit</summary>
   <img src="https://github.com/PROMETHEUS-THEGHOST/AI-virtual-cursor-" alt="proton exit" width="250" height="auto">
  <ul>
    <li>
      <code> Proton Exit </code> <br>
      Terminates the voice assisstant thread. GUI window needs to be closed manually.
    </li>
  </ul>
</details>

# Getting Started

  ### Pre-requisites
  
  Python: (3.6 - 3.8.5)<br>
  Anaconda Distribution: To download click [here](https://www.anaconda.com/products/individual).
  
  ### Procedure
  ```bash
  git clone gh repo clone PROMETHEUS-THEGHOST/AI-virtual-cursor-
  ```
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


 # Collaborators
  | |  |  |  |  |
  | ------------- | ------------- | ------------- | ------------- | ------------- |
  | VAISAKH | [GitHub](github.com/PROMETHEUS-THEGHOST) | [Email](mailto:vaisakhs2255@gmail.com) | [LinkedIn](https://www.linkedin.com/in/vaisakh-sriram-860992213) | [Instagram](https://www.instagram.com/_vaisakhsriram?igshid=ZDdkNTZiNTM=) |
  | RITHESH | [Github] | [Email](ritheshparameswaran3@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rithesh-parameswaran-651935260) | [Instagram] |
  | KARUN | [GitHub] | [Email] | [LinkedIn](https://www.linkedin.com/in/karun-krishnan-9ab74b245) | Instagram |
  
