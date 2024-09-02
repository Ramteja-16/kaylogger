# Keylogger

## Description

This project is a simple keylogger written in Python. It captures keyboard inputs and logs them for monitoring purposes. Please note that this keylogger is intended for educational purposes only. Unauthorized use of this software can be illegal and unethical.

## Installation

To use this keylogger, you need to have Python installed on your system. Follow these steps to set up the keylogger:

1. Clone the repository:
    ```bash
    git clone https://github.com/Ramteja-16/keylogger.git
    ```

2. Navigate to the project directory:
    ```bash
    cd keylogger
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## How It Works

The keylogger works by using Python's `pynput` library to monitor and record keyboard events. It listens for keystrokes and appends them to a log file (`log.txt`) stored in the same directory as the script.

Key points of its operation:
- **Keyboard Listener**: The keylogger uses a keyboard listener to capture each key pressed.
- **Log File**: All captured keystrokes are saved in a plain text file named `log.txt`.
- **Stealth Mode**: The keylogger runs in the background without displaying any visible windows or notifications.

## How to Use

1. **Run the Keylogger**:
    To start logging keystrokes, run the `keylogger.py` script:
    ```bash
    python keylogger.py
    ```

2. **Stop the Keylogger**:
    To stop the keylogger, you can manually terminate the process from your terminal or task manager.

3. **View the Logs**:
    After stopping the keylogger, open the `log.txt` file in the same directory to review the recorded keystrokes.

### Important Notes:

- **Ensure Proper Use**: Only use this software on systems where you have permission to monitor activity.
- **Ethical Considerations**: Unauthorized use can be illegal and unethical. Make sure you comply with all relevant laws and regulations.

## Features

- Logs all keystrokes to a file.
- Runs silently in the background.
- Can be customized to log specific types of keystrokes or add timestamps.

## Disclaimer

This software is intended for educational purposes only. The author does not condone the use of this tool for malicious or unauthorized activities. Use this software at your own risk and ensure that you comply with all applicable laws and regulations in your jurisdiction.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
