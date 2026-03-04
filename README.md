Here's the full copy-paste text version:

---

# Python Mini Projects — Code With Harry Series

**Version 1.0 | Open Source — MIT License | Python 3.8+**

---

## 1. Project Overview

This repository is a curated collection of seven Python mini projects developed as part of the Code With Harry tutorial series. Each project is self-contained, progressively increases in complexity, and demonstrates a distinct set of Python concepts — ranging from CLI game logic and file system automation to GUI application development and desktop notifications.

| # | Project | Description | Key Library |
|---|---------|-------------|-------------|
| 1 | Snake Water Gun Game | CLI game — Python twist on Rock Paper Scissors | random |
| 2 | File Organiser | Auto-sorts files into folders by type | os, shutil |
| 3 | Typing Speed Tester | Measures WPM and accuracy in the terminal | time, random |
| 4 | Quiz App | Multiple-choice quiz with live scoring | Built-in |
| 5 | PDF Merger | GUI app to select and merge PDF files | tkinter, pypdf |
| 6 | Water Drinking Reminder | Desktop notification reminder on a timer | plyer |
| 7 | Password Manager | Save and retrieve passwords from a local file | pyperclip |

---

## 2. Getting Started

**Prerequisites**
- Python 3.8 or higher installed
- pip package manager available
- A terminal / command prompt

**Installation**

Clone the repository to your local machine:

```
git clone https://github.com/your-username/python-cwh-projects.git
cd python-cwh-projects
```

---

## 3. Project Details

### Project 1: Snake Water Gun Game
**File:** `mini project 1 Chinese water gun snake game/ChineseSWG_Game.py`

A command-line game based on the classic Chinese hand game — Snake, Water, Gun. The player picks one of three options and competes against a randomly generated computer choice.

**Rules:**
- Snake drinks Water
- Water douses Gun
- Gun shoots Snake

**Run:**
```
python "mini project 1 Chinese water gun snake game/ChineseSWG_Game.py"
```

---

### Project 2: File Organiser
**File:** `mini project 2 file organiser/fileorganiser.py`

Automatically scans the current working directory and sorts files into categorised subfolders — PDFs, Images, Videos, Word Files, and Text Files — based on file extension.

**Note:** Run this inside the folder you want to organise. It will move files in place.

**Run:**
```
cd "mini project 2 file organiser"
python fileorganiser.py
```

---

### Project 3: Typing Speed Tester
**File:** `mini project 3/speedTester.py`

Presents the user with a randomly selected sentence and measures how fast and accurately they reproduce it. Outputs words per minute (WPM) and character-level accuracy as a percentage.

**Run:**
```
python "mini project 3/speedTester.py"
```

---

### Project 4: Quiz App
**File:** `mini project 4 quiz app/quizapp.py`

A terminal-based multiple-choice quiz covering general knowledge topics. Tracks the user's score in real time and displays a final summary upon completion.

**Run:**
```
python "mini project 4 quiz app/quizapp.py"
```

---

### Project 5: PDF Merger
**File:** `mini project 5/pdfmerger.py`

A desktop GUI application built with tkinter that enables users to select multiple PDF files via a file dialog and merge them into a single output PDF using the pypdf library.

**Install dependencies:**
```
pip install pypdf
```

**Run:**
```
python "mini project 5/pdfmerger.py"
```

---

### Project 6: Water Drinking Reminder
**File:** `mini project 6 water drinking reminder/water_reminder.py`

A lightweight background script that sends a cross-platform desktop push notification every 30 minutes reminding the user to drink water. Powered by the plyer library for OS-level notification support.

**Install dependencies:**
```
pip install plyer
```

**Run:**
```
python "mini project 6 water drinking reminder/water_reminder.py"
```

---

### Project 7: Password Manager
**File:** `mini project 7/passwordManager.py`

A simple CLI password manager that persists website-password pairs to a local text file. Users can retrieve any saved password, which is automatically copied to the system clipboard via pyperclip.

**Note:** Passwords are stored in plain text. This project is for educational purposes only — do not use it for real credentials.

**Install dependencies:**
```
pip install pyperclip
```

**Run:**
```
python "mini project 7/passwordManager.py"
```

---

## 4. Technology Stack

| Category | Tools & Libraries |
|----------|------------------|
| Language | Python 3.8+ |
| GUI Framework | tkinter |
| PDF Handling | pypdf |
| Notifications | plyer |
| Clipboard | pyperclip |
| Standard Library | os, shutil, time, random |

---

## 5. Learning Objectives

| Concept | Application |
|---------|-------------|
| Functions, Conditionals & Loops | Core Python control flow and reusable functions |
| File I/O | Reading and writing files using open() and shutil |
| OS Interaction | Automating file and directory tasks via the os module |
| GUI Development | Building desktop applications with tkinter |
| Desktop Notifications | Sending cross-platform alerts using plyer |
| Input Timing & Accuracy | Measuring typing speed and precision in real time |
| Clipboard Interaction | Programmatic copy-paste via pyperclip |

---

## 6. Acknowledgements & License

Projects built following the Code With Harry Python tutorial series. Refer to codewithharry.com for video walkthroughs and course material.

This repository is open source and distributed under the MIT License. See the LICENSE file in the root of the repository for full terms.
