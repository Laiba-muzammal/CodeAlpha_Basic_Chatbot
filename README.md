# 🤖 Basic Chatbot using NLTK

A beginner-friendly chatbot built using Python's `nltk.chat.util.Chat` module.

---

## 🎯 Features

- Responds to greetings, jokes, facts, and general questions
- Uses pattern-based responses
- Includes fallback messages
- Easy-to-extend conversation patterns
- Interactive CLI-based chat

---

## 🧠 Technologies Used

- Python
- NLTK (`nltk.chat.util`)
- Regex for pattern matching

---

## 🗂️ Project Structure

```bash
nltk_chatbot/
├── main.py # Main Python script containing the chatbot logic
└── README.md # Project documentation
```

---

## 🚀 How to Run

#### 1. Make sure Python and NLTK are installed:
```bash
pip install nltk
```

#### Run the chatbot:
```
python chatbot.py
```

---

### 📚 Example:
```
************CHATBOT*************
Chatbot: Hello! I am your Chatbot. Ask me anything.
(Note: Enter exit to end the conversation.)

You: hello
Chatbot: Hello! How are you?

You: Tell me a fact
Chatbot: Octopuses have three hearts.

You: bye
Chatbot: Bye! Have a nice day
```

---

### 🔧 Extend Patterns:
You can add more conversational patterns in the conversation list like this:

```
[r"How are you?", ["I'm just a bunch of code, but I'm doing fine!"]]
```

---

### ✅ Use Cases:
Beginners exploring Natural Language Processing (NLP)

Academic or demo projects

Fun interactive mini-game in terminal

---

##### 👩‍💻 Built with ❤️ using NLTK and Python
