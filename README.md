# Simple-Chat-Bot
A basic console chatbot written in Python.
It responds to a few simple messages like greetings and questions.

This is a very simple chatbot written in Python.  
It runs in the terminal and responds to basic inputs like greetings or questions.

## ✅ Features

- Works directly in the terminal (no web interface)
- Responds to:
  - "what is your name"
  - "how are you"
  - "thank you"
  - "goodbye", "exit", "quit", etc.
- Easy to edit and expand

## 🛠️ Requirements

- Python 3
 the code
print("welcome to your chat bot")
while True:
  User_input = input("you : ")
  if User_input.lower() in ["good luck", "goodbye", "exit", "quit"]:
    print("chat bot : goodbye")
    break
  elif "what is your name" in User_input:
    print("chat bot : my name is chat bot")
  elif "how are you" in User_input:
    print("chat bot : i am fine")
  elif "thank you" in User_input:
    print("chat bot : you are welcome")
  else:
    print("chat bot : sorry i did not understand that")
