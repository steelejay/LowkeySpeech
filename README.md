# LowkeySpeech
Google Speech Recognition API in Unity (C#)

Requires an API Key from: https://console.cloud.google.com/apis/

## Installation and configuration

- Clone this repository

- Import the project folder in Unity Game Engine

- Go to EDIT -> PROJECT SETTINGS -> PLAYER -> API COMPATIBILITY LEVEL and select **.NET 2.0**

- Go to [this file](/Unity%20Demo%20Project/GoogleSpeechTest/Assets/Scripts/GoogleVoiceSpeech.cs) 

- Find this piece of code and append your Google api key 
 
  > string apiURL = "https://speech.googleapis.com/v1/speech:recognize?&key=";
 
   **so it should look like this**
 
   > string apiURL = "https://speech.googleapis.com/v1/speech:recognize?&key=yourapikeyhere";
   
 - Run the project and it should be working just fine
 
 
 
 
 Made by **steelejay** and updated by **LukasMeine**
