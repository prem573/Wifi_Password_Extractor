# Wi-Fi Extractor

## A Tool That Shows All Wifi Passwords In Your Device 

Wi-Fi Extractor is a Python tool for retrieving information about Wi-Fi profiles and, if authorized, their passwords on Windows systems.

This tool makes use of the `subprocess` module to interact with the Windows command line and obtain information about Wi-Fi profiles, including the SSID and, when authorized, the network key.

## Features

- Retrieves a list of all available Wi-Fi profiles on the Windows system.
- Displays the SSID (network name) of each Wi-Fi profile.
- Optionally, provides the network key (password) for each Wi-Fi profile when authorized.

## Prerequisites

- Python 3.x
- Windows operating system

## Usage

1. Clone the repository:

   ```sh
   git clone https://github.com/prem573/Wifi_Password_Extractor
2. Change The directory:
   ```sh
   cd Wifi_Password_Extractor
3. Run :
  ```sh
python main.py
