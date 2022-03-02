# WQ7Tpanadapter
A very enhanced panadapter program for the Raspberrypi based on the original FreqShow


INSTALLATION of DEPENDENCIES
!VERY IMPORTANT!

Instructions updated for Raspberry Pi OS 64-bit Bullseye

Please note, the enhancements to the original FreqShow by WQ7T require the Python-Scipy
Library in addition to the original dependencies for FreqShow.

Original dependencies required by Adafruit/FreqShow
https://learn.adafruit.com/freq-show-raspberry-pi-rtl-sdr-scanner/installation
install scripts:

https://www.scipy.org/install.html

install script :
```console
sudo apt-get update
sudo apt-get install cmake build-essential libusb-1.0-0-dev git pandoc rtl-sdr librtlsdr-dev
sudo apt-get install python3-numpy python3-scipy python3-matplotlib python3-ipython python3-pandas python3-sympy python3-nose
sudo pip3 install pyrtlsdr
```

Run the program:
```console
python3 freqshow.py
```

READ READ READ THE PDF operating manual it will also show you how to save your own deafault parameters!
