# Keylogger Security Research

## Overview

This project is a **consent-based keylogger demonstration** developed for security research and educational purposes.

The application demonstrates how keystroke logging works by capturing keyboard input **only while the demonstration application is active**. Each captured key is displayed in the application and stored locally with a timestamp.

## Objectives

* Understand the basic concept of keystroke logging.
* Demonstrate how keyboard input can be captured by an application.
* Record keystrokes with timestamps for research purposes.
* Understand the security and privacy risks associated with keylogging.
* Learn about defensive measures against unauthorized keylogging.

## Technologies Used

* **Python**
* **Tkinter** – graphical user interface
* **datetime** – timestamp generation

## Features

* Captures keyboard input within the application.
* Displays captured keys in the application window.
* Records timestamps for each captured key.
* Stores demonstration logs locally.
* Provides a simple graphical interface.

## How It Works

1. The application creates a Tkinter window.
2. Keyboard events inside the application are detected.
3. The pressed key is identified.
4. A timestamp is generated.
5. The key and timestamp are written to a local log file.
6. The captured key is displayed in the application.

## How to Run

Make sure Python 3 is installed.

Run:

```bash
python keylogger.py
```

The application window will open. Type inside the application window to test the key capture functionality.

## Security and Ethical Considerations

This project is intended **only for authorized security research, education, and demonstration**.

It does not attempt to monitor other applications, collect passwords from other programs, or operate covertly. Test data should not contain real passwords, personal information, or other sensitive information.

## Project Structure

```text
Keylogger-Security-Research/
├── README.md
└── keylogger.py
```

## Future Improvements

* Add Start/Stop recording controls.
* Add a log viewer.
* Add log-clearing functionality.
* Add security alerts for suspicious keylogging behavior.
* Develop a defensive keylogger detection component.
* Improve the user interface.

## Disclaimer

This project is created for educational and authorized security research purposes. It should not be used to monitor or collect information from other people without their knowledge and permission.
