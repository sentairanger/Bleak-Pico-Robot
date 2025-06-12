# Bleak-Pico-Robot
This project allows you to control a Raspberry Pi Robot with a Raspberry Pi Pico W.

## Getting Started

First you will need a Pi. Any Pi with Bluetooth will work just fine. I used a Pi 3B+ in my tests. You'll also need a Pico W with the latest version of Micropython. Next, you will need a separate virtual environment on the Pi. You can create one, preferably with using the system libraries with `python3 -m venv blue --system-site-packages`. Then activate with `source blue/bin/activate`. Next, rename the Pico code to `main.py` to run the code on boot. Boot the Pico first and then run the code on the Pi. And you should be able to control the Robot. Note, you will need to copy the `picozero.py` file from the official repository on to the Pico for safekeeping as the picozero library doesn't seem to work properly.
