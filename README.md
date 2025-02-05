# Cisco-Configuration-Deployment

## Introduction

This Python script is designed to facilitate the copying of templates to Cisco routers or switches via console connection. It provides a simple interface for selecting the COM port, baud rate, and entering the password required for accessing privileged EXEC mode on the device. The script then copies the specified template file to the device and generates a log file to track the process.

## How it Works

The script establishes a serial connection with the Cisco device using the provided COM port and baud rate. It then sends commands to enter privileged EXEC mode and authenticate using the provided password if necessary. Once in privileged mode, the script reads a template file line by line and sends each line as a command to the Cisco device. After sending all commands, it waits for the device to process them and generates a log file containing the output received from the device.

## Features

- Easy-to-use script for copying templates to Cisco devices via console connection.
- Supports selection of COM port and baud rate.
- Password authentication for privileged EXEC mode access.
- Generates a log file to track the template copying process.

## How to Get Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/cisco-template-copy.git

2. **Navigate to the Directory:**
   ```bash
        cd cisco-template-copy
   
3. **Install Dependencies:**
   ```bash
     Ensure you have Python installed on your system. No additional Python packages are required.

4. **Run the Script:**
    ```bash
    python template_copy.py

5. **Run the Script:**
Follow the on-screen prompts to select the COM port, baud rate, enter the password, specify the template file, and provide a filename for the log file.

6. **Check the Log File:**
Once the script execution is complete, check the generated log file to verify the template copying process.

## Dependencies 
Python 3.x
pyserial (included in Python standard library)

## Demo
https://youtu.be/mnpJAD8dN78

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

This script was created by [Anthony Constant](https://anthonyconstant.co.uk/).

## Support My Work

If you like this repository or have used any of the code, please consider showing your support:

- Give it a star ⭐️ to acknowledge its value.
- You can also support me by [buying me a coffee ☕️](https://ko-fi.com/W7W144CAO).




