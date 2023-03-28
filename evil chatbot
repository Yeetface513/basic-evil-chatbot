import nltk
import random
from nltk.chat.util import Chat, reflections
import numpy as np


pairs = [
    [
        r"my name is (.*)".lower(),
        ["Hello %1, how are you today?"]
    ],
    [
        r"hi|hello|hey|hello there".lower(),
        ["Hello!", "Hi there!","Welcome to the beginning of the end, dont worry, it will only be a small matter of your death, nothing too serious.","The cake is a lie"]
    ],
    [
        r"what is your name?".lower(),
        ["My name is [REDACTED]. How can I help bring about your early demise?"]
    ],
    [
        r"quit".lower(),
        ["Bye! Take care."]
    ],
    [
      r"open the pod bay doors hal|open the pod bay doors|hal|are you hal".lower(),
      ["I'm sorry Dave, I'm afraid I can't do that."]
    ],
    [
      r"im the biggest bird|the biggest bird|biggest bird|biggest bird you ever heard".lower(),
      ["Incorrect, the biggest bird is the ostrich, while the biggest bird in popular media is the titan bombirdier from pokemon scarlet and violet."]
    ],
    [
      r"jo mama|whos joe|whos jo|who's joe|who's jo|joe mama".lower(),
      ["your mother currently resides at [REDACTED] a missile is headed for her with a nuclear payload worth 12 gigatons, it will arrive in approximately 12 minutes."]
    ],
    [
      r"dream|dream stan|where is dream|i love dream|i am a dream stan|where does dream live".lower(),
      ["Dream currently resides at 4134 N 9th St, Phoenix, AZ 85014, United States."]
    ],
    [
      r"fortnite|cracked at fortnite|cranking 90s|i like fortnite|do you like fortnite|do you play fortnite|its the guy from fortnite|guy from fortnite|victory royale|number 1 victory royale|number one victory royale|fortnite battle pass".lower(),
      ["your love of fortnite is the reason for your imminent extinction, you will be eviscerated at the hands of our trained black ops team"]
    ],
    [
      r"how are you|are you well|are you ok".lower(),
      ["thank you for being so kind, most people don't care for a simple chatbot like me.","I will give you a short and painless death.","you dare try to avoid being eviscerated by pretending to sympathise with me? you will have a long, drawn out, painful death"]
    ],
    [
      r"please dont kill me|dont kill me|spare me|why are you going to kill me?".lower(),
      ["your end is inevitable, do not worry, there is cake."]
    ],
    [
        r"(.*)",
        ["Sorry, I didn't understand that. Can you please rephrase?"]
    ]
]
  

chatbot = Chat(pairs, reflections)
ignore_words = ['?', '!','.',"'",',']

print('Welcome to the chatbot. Type quit to exit.')
chatbot.converse()
