# Screenshot Capture Tool

## Overview
This is a simple Python-based Screenshot Capture Tool using **Tkinter** for the graphical user interface and **PyAutoGUI** for capturing screenshots. Users can take screenshots and save them to a desired location through a file dialog.

## Features
- GUI-based screenshot capture
- Save screenshots with a custom filename
- Lightweight and easy to use

## Requirements
Ensure you have Python installed (3.x recommended). The following Python modules are required:

### Required Modules
- **tkinter** (built-in with Python)
- **pyautogui**

### Installation
To install the required module, run:
```bash
pip install pyautogui
```

## Usage
1. Run the script using:
   ```bash
   python screenshot_app.py
   ```
2. Click the **"Take Screenshot"** button.
3. Choose a location to save the screenshot.
4. The screenshot will be saved with the filename you enter followed by `screenshot.png`.

## Notes
- Ensure you have the necessary permissions to save files in the selected directory.
- The program currently appends "screenshot.png" to the chosen filename. You can modify it for better customization.

## Future Enhancements
- Allow users to choose the image format (PNG, JPG, etc.).
- Implement a preview feature before saving the screenshot.
- Add hotkey support for capturing screenshots.

## License
This project is open-source and free to use under the MIT License.

