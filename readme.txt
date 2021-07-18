1. Install pycharm
2. Install library
    pip install chatterbot==1.0.5
    pip install chatterbot_corpus
    pip install pyaudio
    pip install SpeechRecognition
3. Run in terminal : python FinalChatbot.py

------------------------------------------------------------
Types of chatbot:

1.  Rule-based bots
With this type of bot, communication is through pre-set rules. User input must conform to these pre-defined rules in order to get an answer.
2.  NLP of AI Bots
NLP chatbots learn languages in a similar way that children learn a language. After having learned a number of examples,
they are able to make connections between questions that are asked in different ways.Here the bot learn by itself.
Mthodology :
    1.tokenzation
    2.steming
    3.bags of words

This is Rule based chat bot. Created using chatterbox library.
The training of this bot is done via yml file that is corpus custom file(library used for training bot).
Speech Recognition is used for making the bot speak.
pyaudio is used to for taking the input from user microphone.

Interface is implemented using tkinter which is required to create desktop application.
For integrating with websites we need flask or dajango.