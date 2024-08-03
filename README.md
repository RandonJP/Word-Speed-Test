## Features

- **Typing Test**: Type the displayed text as quickly and accurately as possible.
- **Words Per Minute (WPM) Calculation**: Track your typing speed in words per minute.
- **Visual Feedback**: Correct characters are shown in green, and incorrect characters are shown in red.
- **Dynamic Text**: Each round presents a different line of text.

## Requirements

- Python 3.x
- `curses` library (included in standard Python library for Unix-like systems; for Windows, use `windows-curses` package)

## Installation

1. **Clone the Repository** (if applicable):
    ```bash
    git clone https://github.com/yourusername/typing-test.git
    cd typing-test
    ```

2. **Install `windows-curses`** (for Windows users):
    ```bash
    pip install windows-curses
    ```

## Usage

1. **Run the Program**:
    ```bash
    python typing_test.py
    ```

2. **Playing the Game**:
    - **Start Screen**: Press any key to begin the typing test.
    - **Typing**: Type the text displayed on the screen as accurately as possible. Characters you type will appear in green if correct and red if incorrect.
    - **Backspace**: Use the backspace key to correct mistakes.
    - **Quit**: Press `ESC` to exit the game at any time.

3. **End of Game**:
    - After completing the typing test, you will see a thank you message.
    - Press any key to restart the game or `ESC` to quit.
