# 🤖 PyBot - Simple Python Console Chatbot

A lightweight, rule-based conversational chatbot built entirely with standard Python. PyBot demonstrates basic string manipulation, control flow (`if-elif-else`), and user input handling in a terminal interface without external dependencies.

---

## ✨ Features

- **Zero Dependencies:** Built strictly using Python's standard library.
- **Natural Phrase Matching:** Detects keywords across common conversational topics:
  - Greetings & time-of-day wishes (morning, afternoon, evening).
  - General identity questions ("Who made you?", "What is your name?").
  - Mood check-ins (happy, sad, fine).
  - Programming jokes and study advice.
- **Graceful Exit:** Safely ends the loop using keywords like `bye`, `exit`, or `quit`.
- **Fallback Response:** Handles unrecognized inputs smoothly.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have **Python 3.6+** installed on your system. You can verify your version by running:

```bash
python --version

