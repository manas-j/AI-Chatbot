# An-AI-Chatbot-in-Python-and-Flask
An AI Chatbot using Python and Flask REST API 

## Requirements (libraries)
1. TensorFlow
1. Flask

To access the bot on localhost, go to ```http://127.0.0.1:5000/ ``` 

### Execution
To run this Bot, first run the ```train.py``` file to train the model. This will generate a file named ```chatbot_model.h5```<br>
This is the model which will be used by the Flask REST API to easily give feedback without the need to retrain.<br>
After running ```train.py```, next run the ```app.py``` to initialize and start the bot.<br>
To add more terms and vocabulary to the bot, modify the ```intents.json``` file and add your personalized words and retrain the model again.
