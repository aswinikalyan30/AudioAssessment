# AudioAssessment
## A audio-based assessment for visually impaired students with voice authentication model 
This was a project developed as a part of intern-hackathon-2022(india) conducted by @ellucian

### Problem statement:
- Automate assesments for visually impaired persons by reading out the questions for the user and recognizing voice input
- Authenticate users voice by training & testing the model (Model used here is GMM)
- Additional layer of security for foolproof assesment is done by taking snapshots of the user when he answers the question

### About the Project:

#### Requirements
Use ```pip install``` and install the following packages for the project to run:
```
open-cv
os
re
requests
pyttsx3
wave
pickle
pyaudio
warnings
numpy
sklearn ~preprocessing
scipy.io.wavfile
python_speech_features
sklearn.mixture ~GaussianMixture 
time
speech_recognition 
playsound
gtts
```
#### Files
- The base file to run the project is named ``audiobase.py`` which calls functions from other python files
- The ``train.py`` and ``test.py`` have some file paths that is hard-coded and must be changed according to the system to which it is downloaded

#### Data
The data is set up on json-server as an API which you can find in this link:
https://my-json-server.typicode.com/aswinikalyan30/jsonserver

These questions are hard-coded and are all Ellucian-related

To create your own fake-api you can check out:
[JSON Server](https://github.com/typicode/json-server)
