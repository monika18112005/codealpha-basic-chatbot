🧠 Basic Chatbot
📋 Description
This is a simple rule-based chatbot built using Python. It interacts with the user based on predefined responses. The chatbot uses basic programming concepts like functions, if-elif conditions, loops, and input/output handling.

💡 Features
Responds to basic inputs:

"hlo" → "hi"

"how are you" → "I am fine"

"bye" → "Thanks, goodbye!"

Case-insensitive user input

Continues conversation until user types "bye"

🔧 How It Works
The user types a message.

The message is passed to the respond_to_user() function.

Based on the input, the function returns a response.

The loop continues until "bye" is typed.

🧑‍💻 Code Overview
Function: respond_to_user(message)
Accepts user input.

Checks the message using if-elif conditions.

Returns the appropriate response.

Function: run_chatbot()
Starts the conversation.

Uses a loop to repeatedly take user input.

Calls respond_to_user() and prints the response.

Ends when user types "bye".

▶️ How to Run
Make sure you have Python installed.

Save the code in a file (e.g., chatbot.py).

Open your terminal and run:

bash
Copy
Edit
python chatbot.py
📌 Example
vbnet
Copy
Edit
Welcome to the Chatbot! (Type 'bye' to exit)
You: hlo
Bot: hi
You: how are you
Bot: I am fine
You: bye
Bot: Thanks, goodbye!
🛠️ Requirements
Python 3.x

📁 File Structure
bash
Copy
Edit
chatbot.py     # Main chatbot script
README.md      # This file
📚 Concepts Used
if-elif-else statements

Functions

Loops (while)

String manipulation

Input/output

