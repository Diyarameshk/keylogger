
# Keylogger Demonstration Project

## Overview

This project demonstrates the functionality of a keylogger, a program designed to record each keystroke made by a user. The purpose of this project is educational, intended to show how keyloggers work for cybersecurity awareness and ethical hacking studies.

When the Python script is executed, it will capture and log every keypress to a text file named `keyfile.txt`.

## Features

- Records all keystrokes made by the user.
- Saves the recorded keystrokes to a file (`keyfile.txt`).

## Requirements

- Python 
- `pynput` library

## Setup
 **Install the required library:**

  

Ensure you have `pip` installed, then run:

```sh
pip install pynput
```
## Usage

1. **Run the keylogger script:**

    ```sh
    python keylogger.py
    ```

2. **Stop the keylogger:**

    To stop the keylogger, you can manually terminate the script (e.g., by pressing `Ctrl + C` in the terminal).

3. **View the recorded keystrokes:**

    Open the `keyfile.txt` file to see the recorded keystrokes.
