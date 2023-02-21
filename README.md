# alexa
## Build an Artificial Assistant

### Full tutorial (video)
To watch the tutorial, click on the image below

[![Watch the video-- Build your own Alexa](https://img.youtube.com/vi/ZMQg_DL4Fog/0.jpg)](https://youtu.be/ZMQg_DL4Fog "Build your own Alexa")

## Installation
### For windows users
(run those in command prompt/cmt/terminal)
For the robot to listen to our voice/speech
`pip install speechRecognition`

To speak out, or text to speech
`pip install pyttsx3`

For advance control on browser
`pip install pywhatkit`

To get wikipedia data
`pip install wikipedia`

To get funny jokes
`pip install pyjokes`

### For linux users
Learn all the above commands on terminal. Make sure to use `pip3`, because in linux `pip` refers for `python2` and `pip3` refers to `python3`.
Install these too - 
`pip3 install pyAudio`

In case any error pops up install this -
`pip3 install portAudio`

#### Issues
If you encounter any problems feel free to open a new issue. Before that check other closed issues and check if your issue matches with any older issues.



<html>
<body>
  <h1>Alexa Voice Assistant</h1>
  <p>This is a Python program that acts as a voice assistant similar to Amazon's Alexa. The program uses speech recognition to listen for voice commands and performs various actions based on those commands.</p>
  <h2>Features</h2>
  <ul>
    <li>Speech recognition using the SpeechRecognition library</li>
    <li>Text-to-speech using the pyttsx3 library</li>
    <li>Command processing and execution</li>
    <li>YouTube search and play using the pywhatkit library</li>
    <li>Current time announcement</li>
    <li>Wikipedia search using the wikipedia library</li>
    <li>Joke telling using the pyjokes library</li>
    <li>Wake word ("alexa") to activate the assistant</li>
    <li>Error handling for speech recognition</li>
    <li>Stop command ("stop") to exit the program</li>
  </ul>
  <h2>Usage</h2>
  <p>To use the program, run the `main.py` file in a Python environment with the necessary libraries installed. The program will listen for the wake word "alexa" and prompt the user for a command. The user can then speak a command, and the program will execute the appropriate action.</p>
  <p>To stop the program, the user can say "stop".</p>
</body>
</html>
