# Pokemon-QR-Scanner-to-Excel
This Python script scans QR codes in real-time using a webcam, logging unique codes to an Excel file. It uses OpenCV and PyZbar for scanning, and Openpyxl for data logging. Duplication is avoided and scanning events are logged in a .log file. Press 'q' to stop the script.

QR Code Scanner with Excel Logging
This Python script performs real-time QR code scanning using a webcam, logging unique codes to an Excel file. It uses OpenCV and PyZbar for scanning, and Openpyxl for data logging. Duplication is avoided and scanning events are logged in a .log file. Press 'q' to stop the script.

Prerequisites
Python 3.6 or above
OpenCV
PyZbar
Openpyxl
Installation
Install Python from the official site: https://www.python.org/downloads/
Install necessary libraries using pip:
pip install opencv-python
pip install pyzbar
pip install openpyxl


Usage
Run the script using:
python script_name.py
Show QR codes to your webcam.
Press 'q' to stop the script.
Output
The script will create an Excel file named 'qr_codes.xlsx' in the same directory. Each unique QR code scanned will be added to this file.
A log file named 'qr_scanner.log' will be created in the same directory. This file will contain a record of events during the script's runtime.
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
