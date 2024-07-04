# Prodigy_infotech-task-4
# Simple Keylogger

This is a simple keylogger program created as part of Task 4 for my Prodigy Infotech internship. The keylogger records and logs keystrokes, saving them to a file named `keylog.txt` located in the Downloads folder.

## Features

- Captures all keystrokes including special keys.
- Logs the keystrokes with timestamps.
- Stops logging when the `Esc` key is pressed.

## Ethical Considerations

Please note that keyloggers should only be used for ethical purposes, such as personal use or with explicit permission from the device owner. Unauthorized use of keyloggers is illegal and unethical.

## Getting Started

### Prerequisites

- Python 3.x
- `pynput` library

### Installation

1. Clone the repository:

   
    cd simple-keylogger
    

2. Install the `pynput` library:

    ```bash
    pip install pynput
    ```

3. Run the keylogger script:

    ```bash
    python keylogger.py
    ```

### Usage

The keylogger will start logging keystrokes once you run the script. To stop the keylogger, press the `Esc` key. The logged keystrokes will be saved to a file named `keylog.txt` in the Downloads folder.

### Example Log Entry

2024-07-02 21:53:54,457: 'n'
2024-07-02 21:53:54,677: 'o'
2024-07-02 21:53:54,995: 't'
2024-07-02 21:53:55,281: 'h'
2024-07-02 21:53:57,213: Key.backspace
...
2024-07-02 21:54:02,710: 'i'
2024-07-02 21:54:02,965: 'l'
2024-07-02 21:54:03,124: 'l'
2024-07-02 21:54:03,446: Key.space
2024-07-02 21:54:03,799: 'b'
2024-07-02 21:54:04,164: 'e'



