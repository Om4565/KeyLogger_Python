# Python Keylogger (Educational Project)

## Overview

This project is a **basic Python keylogger** developed for **educational and cybersecurity research purposes**.
It demonstrates how keyboard input can be captured using Python and stored in a log file.

The project uses the **pynput library** to monitor keyboard activity and record pressed keys.

This type of project is commonly used in **cybersecurity labs** to understand how keylogging works and how such behavior can be detected and prevented by security tools.

---

## Features

* Captures keyboard input in real time
* Stores logged keys in a file
* Handles special keys such as:

  * Enter
  * Space
  * Shift
  * Caps Lock
  * Backspace
* Saves logs inside the **Windows AppData directory**

---

## Technologies Used

* Python 3
* pynput library

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/python-keylogger.git
cd python-keylogger
```

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the script:

```bash
python KeyLogger.py
```

The captured keystrokes will be saved in:

```
C:\Users\<username>\AppData\Roaming\processmanager.txt
```

---

## Project Purpose

This project was created as part of **learning Python and cybersecurity concepts** including:

* Input monitoring
* Malware behavior analysis
* Defensive security research
* Understanding how keylogging attacks work

---

## Disclaimer

This project is created **strictly for educational purposes and security research**.

The author is **not responsible for any misuse** of this code.
Do not use this software on systems without proper authorization.

---

## Author
Om Mohite.
| Web Application Security | Python Security Tools
