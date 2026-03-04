# 🐍 Python Mini Projects — Code With Harry Series

A collection of 7 beginner-to-intermediate Python mini projects built while following the [Code With Harry](https://www.codewithharry.com/) Python tutorial series. Each project explores a different aspect of Python — from game logic and file I/O to GUI applications and system notifications.

---

## 📁 Projects Overview

| # | Project | Description | Key Library |
|---|---------|-------------|-------------|
| 1 | [Snake Water Gun Game](#1-snake-water-gun-game) | CLI game — Python twist on Rock Paper Scissors | `random` |
| 2 | [File Organiser](#2-file-organiser) | Auto-sorts files into folders by type | `os`, `shutil` |
| 3 | [Typing Speed Tester](#3-typing-speed-tester) | Measures WPM and accuracy in the terminal | `time`, `random` |
| 4 | [Quiz App](#4-quiz-app) | Multiple-choice quiz with live scoring | — |
| 5 | [PDF Merger](#5-pdf-merger) | GUI app to select and merge PDF files | `tkinter`, `pypdf` |
| 6 | [Water Drinking Reminder](#6-water-drinking-reminder) | Desktop notification reminder on a timer | `plyer` |
| 7 | [Password Manager](#7-password-manager) | Save and retrieve passwords from a local file | `pyperclip` |

---

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip

### Installation

Clone the repository and install any required dependencies for the project you want to run:

```bash
git clone https://github.com/your-username/python-cwh-projects.git
cd python-cwh-projects
```

---

## 📌 Project Details

### 1. Snake Water Gun Game
> `mini project 1 Chinese water gun snake game/ChineseSWG_Game.py`

A command-line game based on the classic Chinese hand game — Snake, Water, Gun. The player picks one of three options and competes against a randomly generated computer choice.

**Rules:** Snake drinks Water · Water douses Gun · Gun shoots Snake

```bash
python "mini project 1 Chinese water gun snake game/ChineseSWG_Game.py"
```

---

### 2. File Organiser
> `mini project 2 file organiser/fileorganiser.py`

Automatically scans the current working directory and sorts files into categorised subfolders (PDFs, Images, Videos, Word Files, Text Files) based on their extension.

```bash
cd "mini project 2 file organiser"
python fileorganiser.py
```

> ⚠️ Run this inside a folder you want to organise — it will move files in place.

---

### 3. Typing Speed Tester
> `mini project 3/speedTester.py`

Presents the user with a random sentence and measures how fast and accurately they type it. Outputs words per minute (WPM) and character-level accuracy.

```bash
python "mini project 3/speedTester.py"
```

---

### 4. Quiz App
> `mini project 4 quiz app/quizapp.py`

A terminal-based multiple-choice quiz covering general knowledge. Tracks the user's score and displays it at the end.

```bash
python "mini project 4 quiz app/quizapp.py"
```

---

### 5. PDF Merger
> `mini project 5/pdfmerger.py`

A GUI application built with `tkinter` that lets users select multiple PDF files and merge them into a single output file using a file dialog.

**Install dependencies:**
```bash
pip install pypdf
```

```bash
python "mini project 5/pdfmerger.py"
```

---

### 6. Water Drinking Reminder
> `mini project 6 water drinking reminder/water_reminder.py`

A background script that sends a desktop push notification every 30 minutes reminding you to drink water. Uses `plyer` for cross-platform notification support.

**Install dependencies:**
```bash
pip install plyer
```

```bash
python "mini project 6 water drinking reminder/water_reminder.py"
```

---

### 7. Password Manager
> `mini project 7/passwordManager.py`

A simple CLI password manager that saves website-password pairs to a local text file. Retrieve any saved password and have it automatically copied to your clipboard.

**Install dependencies:**
```bash
pip install pyperclip
```

```bash
python "mini project 7/passwordManager.py"
```

> ⚠️ Passwords are stored in plain text. This project is intended for learning purposes only — do not use it to store real credentials.

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **GUI:** tkinter
- **Libraries:** `pypdf`, `plyer`, `pyperclip`, `os`, `shutil`, `time`, `random`

---

## 📚 Learning Objectives

Through these projects, the following Python concepts are covered:

- Functions, conditionals, and loops
- File reading and writing (`open`, `shutil`)
- Working with the OS (`os` module)
- Building GUIs with `tkinter`
- Sending desktop notifications
- Timing and measuring user input
- Clipboard interaction

---

## 🤝 Acknowledgements

Projects built following the **Code With Harry** Python tutorial series.  
Check out the series at [codewithharry.com](https://www.codewithharry.com/).

---

## 📄 License

This repository is open source and available under the [MIT License](LICENSE).
