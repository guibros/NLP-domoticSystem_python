# Voice-commanded Domotic System

A Tkinter GUI that can run on a Raspberry Pi to activate the GPIO on a connected objet; like a Raspberry Pi or a microcontroller. Vocal and touch commands (buttons). All commands go through a MQTT server. The target RPi or MCU sends back the change of state through the same MQTTserver. The GUI shows the state of each component on the RPi or the MCU. The outcoming and incoming activities are saved to a database on the commmanding unit: MongoDB.  Command are vocally confirmed.  Meteo connected through Open Weather Map.


<img width="149" alt="image" src="https://user-images.githubusercontent.com/116329812/206030143-28ef334b-b17a-4d47-9434-b2c6c6b10bad.png">

- Run on Linux/Ubuntu
- Start by running project_mainframe2.py in a terminal

module:
fuzzywuzzy
PicoTTS
PIL
paho.mqtt.client
pymongo
RPISim
tkinter
threading
pyowm
time
datetime
requests
os

