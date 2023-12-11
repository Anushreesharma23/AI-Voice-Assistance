# AI-Voice-Assistance
AI voice assistance with the help of python modules.
Alexa Personal Assistant
Alexa is a simple voice-controlled personal assistant developed using Python. It leverages various libraries such as pyttsx3 for text-to-speech, speech_recognition for voice recognition, and other modules for additional functionalities. This assistant can perform tasks like telling jokes, providing information from Wikipedia, opening websites, sending emails, and more.

Setup
Install the required Python libraries:

bash
Copy code
pip install pyttsx3 speechRecognition wikipedia pyjokes
Ensure that you have a working microphone for voice commands.

Usage
Run the alexa.py script in a Python environment:

bash
Copy code
python alexa.py
Alexa will greet you based on the time of day and wait for your voice commands.

Available Commands
Greeting: Alexa responds to "hello" or "hi" with a friendly greeting.
Jokes: Ask Alexa to tell you a joke by saying "joke."
Date: Get the current date by saying "date."
Introduction: Ask Alexa about itself by saying "who are you" or "what can you do."
Creator: Inquire about Alexa's creator by asking "who made you" or "who created you."
Wikipedia Search: Search Wikipedia by saying "Wikipedia" followed by your query.
Open Websites: Open YouTube, Google, or Stack Overflow by saying "open YouTube," "open Google," or "open Stack Overflow."
Play Music: Play music stored in the specified directory by saying "play music."
Time: Ask Alexa for the current time by saying "the time."
Open Code Editor: Open the Visual Studio Code editor by saying "open code."
Send Email: Send an email to a specified recipient by saying "email to [recipient's name]."
Note
Ensure that you replace the email credentials in the sendEmail function with your own email information.
Customize the script to suit your preferences and add new functionalities as needed.







