# CS2 Bhop Script

This is a Bunny Hop (Bhop) script for Counter-Strike 2 (CS2) that automates jumping while holding the space bar, providing a smoother and more consistent bunny hopping experience.

## Features

- Automatically jumps when the space bar is held down
- Simple and lightweight script
- Fetches the latest game offsets from an online repository

## Installation

1. **Make a folder on  your desktop**

    ```bash
    Make a folder on your desktop
    Put the executable into that folder
    ```

## Usage

1. **Ensure that Counter-Strike 2 (cs2.exe) is running.**

2. **Run the executable**

    ```bash
    Ollubhop.exe
    ```

3. **Hold down the space bar to activate the bunny hop.**

## Script Explanation

The script works by:
- Searching for the `cs2.exe` process.
- Fetching the memory offsets required for jumping from an online repository.

### Code Overview

- `fetch_offsets()`: Fetches the latest game offsets from an online repository.
- `get_cs2_process()`: Retrieves the `cs2.exe` process.
- `get_client_module(pm)`: Gets the `client.dll` module from the process.
- `bhop()`: Main function that handles the bunny hopping logic.

### Error Handling

The script includes error handling for various exceptions, including process not found, module not found, memory read/write errors, and more.


## Disclaimer

This script is for educational purposes only. Use it at your own risk. The author is not responsible for any consequences resulting from the use of this script, including but not limited to game bans or other punitive actions by game administrators.
