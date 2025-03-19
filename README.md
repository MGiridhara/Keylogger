A keylogger (short for keystroke logger) is a type of surveillance software or hardware device that records every keystroke made on a keyboard. Keyloggers can be used for both legitimate and malicious purposes.

Types of Keyloggers:-
1.Software Keyloggers – Installed on a device and records keystrokes silently.
2.Hardware Keyloggers – Physical devices connected to keyboards that capture input.

Keylogger: Python Keylogging Script

Disclaimer:-
This script is for **educational purposes only**. Unauthorized use of keyloggers for monitoring others without their consent is **illegal** in many jurisdictions. Use responsibly.


About This Script:-
This is a **Python-based keylogger** that captures and logs keystrokes using the 'pynput' library. It writes recorded keystrokes to a file (log.txt).


How It Works:-
- Listens for keyboard events (key presses and releases).
- Logs pressed keys to 'log.txt'.
- Stops recording when the 'Esc' key is pressed.


Requirements:-
Make sure you have Python installed and install the required package:
```bash
pip install pynput



Usage:-
1. Run the script:
   bash
   python keylogger.py
   
2. Press keys, and they will be logged into `log.txt`.
3. Press 'Esc' to stop the keylogger.


How to Detect & Prevent Keyloggers
If you suspect a keylogger is running on your system, consider:
- Checking for unusual background processes.
- Using antivirus software to scan for suspicious activity.
- Reviewing 'log.txt' for unauthorized logging.

