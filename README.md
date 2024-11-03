# Image-Based Auto Clicker

## Overview
The Image-Based Auto Clicker is a powerful tool that automates clicking based on image recognition. Developed with Python, it provides a user-friendly graphical interface built using CustomTkinter, making the setup and operation simple and intuitive. This auto clicker allows users to specify custom images, set offsets, and click locations dynamically, helping automate repetitive clicking tasks in an intelligent way.

With the Image-Based Auto Clicker, you can:

- Upload or paste images for the clicker to search for on your screen.
- Automate clicks on those images, with configurable positions and offsets.
- Customize BlueStacks integration for quick emulator adjustments.
- Save and load clicker configurations to easily resume automation.

This application aims to make repetitive tasks easier, whether you are gaming, filling out forms, or just in need of a helpful automation tool.

## Features

- **Image Recognition Click Automation**: Upload images that you want the clicker to recognize and act upon.
- **Clipboard Integration**: Paste images directly from your clipboard into the application.
- **Offset Control**: Customize the click positions by adding X and Y offsets for precise automation.
- **BlueStacks Integration**: Adjust BlueStacks window size directly from the app for seamless Android emulator automation.
- **User-Friendly GUI**: Simple, elegant GUI using CustomTkinter for easy interaction.
- **Save and Load Configurations**: Store your automation setups and load them again for quick resumption.

## Installation
To run the Image-Based Auto Clicker, ensure Python 3.9+ is installed. You will also need several Python libraries which can be installed via pip:

```sh
pip install customtkinter opencv-python numpy pyautogui Pillow pywin32
```

### Clone the Repository
To get started, clone the repository from GitHub:

```sh
git clone https://github.com/21Suspect/ImageBasedAutoClicker.git
```

### Install Dependencies
Install the required Python libraries by running:

```sh
pip install -r requirements.txt
```

## Usage

### Launch the Application
To start the auto clicker, navigate to the project directory and run the main script:

```sh
python auto_clicker.py
```

The graphical user interface (GUI) will open, allowing you to upload or paste images, set offsets, adjust BlueStacks window size, and start automating clicks.

### Basic Steps
1. **Upload Images**: Click "Upload Images" to select images that the clicker will look for on the screen.
2. **Paste from Clipboard**: Alternatively, use "Paste Image from Clipboard" to paste images directly from your clipboard.
3. **Set Offsets**: Adjust the X and Y click offsets to refine the clicking position relative to the detected image.
4. **BlueStacks Size Adjustment**: Use the "Set BlueStacks Size" feature to optimize your emulator for automation.
5. **Arm the Clicker**: Use the "Arm Clicker" switch to start automated clicking on matching image positions.

## Configuration
The application has several configurable parameters:

- **Threshold**: Set the image match threshold (default is `0.9`) to fine-tune how strictly the clicker matches your provided images.
- **Click Offsets**: Set X and Y offsets to adjust where the click happens relative to the detected image.
- **Sleep Time**: Set the delay between each click cycle to prevent overwhelming the system (default is `0.5` seconds).

## Important Information
- This tool is intended for automating repetitive clicking tasks that can be tedious for users.
- Use responsibly and ensure compliance with any guidelines or terms of use for the programs you are automating.

## Download Executable Version
You can download the compiled executable version of Image-Based Auto Clicker if you prefer not to run the Python script. This version does not require Python to be installed and can be run directly on your Windows system.

[Download ImageBasedAutoClicker.exe]([https://github.com/21Suspect/ImageBasedAutoClicker/releases](https://github.com/21Suspect/ImageBasedAutoClicker/releases/download/v1.0/ImageBasedAutoClicker.exe))

## Screenshot
Below is a screenshot of the Image-Based Auto Clicker in action:

![Screenshot of Image-Based Auto Clicker](https://github.com/21Suspect/ImageBasedAutoClicker/blob/main/screenshot.png)

## Contributing
Contributions are welcome! If you encounter any bugs, have feature requests, or wish to contribute to the project, please create an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, feel free to reach out to Fabian Vinke at [fabivinke@gmail.com](mailto:fabivinke@gmail.com).

Thank you for using the Image-Based Auto Clicker! If you found this project helpful, please leave a star on the repository. 😊
