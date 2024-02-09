#QR Code Generator

This Python script generates a QR code for a given input link using the qrcode library.

Prerequisites

Make sure you have the following dependencies installed:

Python
qrcode library
You can install the qrcode library using:


pip install qrcode

Getting Started

Clone the repository:
git clone https://github.com/Developer1010x/QR_Code_Generator.git
cd QR_Code_Generator

python generate_qrcode.py
Enter the link when prompted.
The generated QR code will be saved as qrcode001.png in the script's directory.

Usage

Enter the link you want to encode into the QR code when prompted.
The script generates a QR code with a black foreground and a white background.
Customization

You can customize the script by modifying the following parameters in the script:

version: Set the version of the QR code.
box_size: Set the size of each box in the QR code.
border: Set the border size of the QR code.
fill: Set the color of the QR code's foreground.
back_color: Set the color of the QR code's background.
img.save('qrcode001.png'): Change the output file name as needed.



Acknowledgments

qrcode library: GitHub - lincolnloop/python-qrcode
