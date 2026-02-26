# Timber Chatbot v2

## Description

Timber Chatbot v2 is a Python GUI chatbot project created for learning and experimentation purposes.
It combines several small features such as utilities, web data fetching, and simple interactive tools inside one desktop application.

The project mainly focuses on practicing Python integration between different libraries and technologies.

---

## Features

* Basic chatbot with JSON-based responses
* Movie suggestions and comparison
* Simple mini games (dice, coin flip, rock–paper–scissors)
* Mathematical expression calculation
* Text translation
* Unit conversion
* News headline fetching
* Web search using API and Selenium
* Text-to-speech responses
* Chat logging

---

## Technologies Used

* Python
* Tkinter (GUI)
* Requests & BeautifulSoup
* Selenium
* SymPy
* Pint
* pyttsx3
* JSON files for storage

---

## Project Structure

```
timber2.py        # chatbot logic
gui.py            # graphical interface
datastore.json    # questions and answers
movies.json       # movie dataset
chat_log.txt      # saved conversations
```

---

## Installation

Install required packages:

```
pip install requests beautifulsoup4 deep-translator pint feedparser sympy pyttsx3 selenium speechrecognition pillow
```

ChromeDriver is required for Selenium features.

---

## Run

```
python gui.py
```

---

## Notes

This project was built mainly for practice and learning purposes rather than production use.
