# EmotionPredictor
  Emotion Predictor is an Android app for tracking mood and emotions over time using Physiological Signals from an individual. 

# Process to predict emotions of an individual using Emotion Predictor App:
  For the prediction of emotions, Internet of Things(IoT) device is used to get pulse rate.
  The Pulse sensor is placed in the wrist of an individual -> the sensor collects the pulse signals -> The signal is processed to get the form of beat per minute and sent through ESP8266 Wifi Module into the Firebase cloud system.
  The app gets the data stored in the Firebase cloud -> then it sends data to ML model through Flask API -> ML model that can predict the emotions accurately or near to the induced emotions for the sent data -> Result is sent back to the app
  The ML model involves SVM algorithm, which is used to classify positive(happy or calm) and negative(sad or anxious) emotions from the trained data. Then the app fetches the result gained from ML model and displays the status in the app. 

# Additional Features of the App:
This app also includes several features for managing entries and reminders, such as a login and registration system, a calendar for date and time picking, and a CRUD (Create, Read, Update, Delete) page for adding and modifying entries.

# App Modules: 
• Login and registration using Firebase Authentication 
• Context menu with options for team details, About the project, and more
• Popup menu with options to know the contact details and team members
• Calendar for date and time picking, with alerts and reminders that give status notifications to remind to journal
• CRUD page with options for creating, editing, and deleting entries, using SQLite to store data locally on the device
• Mood tracker that allows users to enter a date and write how they feel on that day, along with an optional photo or image

# Project Demo: 
https://youtu.be/fE8ZT2pip2E
