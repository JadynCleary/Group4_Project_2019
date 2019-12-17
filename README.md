# Raspberry Pi DOTMatrix Twitter Grabber

## **Project Description:**

  We linked an LED board to a school twitter account for the purpose of relaying announcements to the student body. For this project, we used various libraries to aid us in developing our code as well as relying on code examples from projects similar to ours. The project required us to work together to pull tweets from the internet, program, and wire the LED board, as well as build a containment unit.

## **Materials necessary:**
* Raspberry Pi 3

* Flexible Adafruit DotStar Matrix 8x32 - 256 RGB LED Pixels

* Wood or acrylic (optional for containment unit)

## **Raspberry Pi 3 GPIO Pins**
![Pins](https://raw.githubusercontent.com/JadynCleary/Group4_Project_2019/master/pi3_gpio.png)

## **Libraries Needed:**

### Apa102 driver:
This will allow you to easily download the subsequent library. To instal Python 3, go to this [link](https://pimylifeup.com/raspberry-pi-led-strip-apa102/) and follow the instructions through step #3 or just copy and paste the following commands into your device’s terminal:

>sudo apt-get update

>sudo apt-get upgrade

>sudo apt-get install python3 python3-dev python3-pip

>sudo pip3 install apa102-pi

### Beautiful Soup 4:
This is a Python library for pulling data from HTML and XML files. To download this library, follow the instructions on this [link](https://www.pythonforbeginners.com/beautifulsoup/beautifulsoup-4-python) or enter the following commands into your device’s terminal:

>apt-get install python-bs4

>easy_install beautifulsoup4

>pip install beautifulsoup4

## **Project Roles:**
### Jorge:
* Wiring & soldering

* Writing a macros to launch python code

### Trevor:
* Translating strings to the LED matrix

### Connor:
* Pulling tweets and converting them into a text file

### Elias:
* Designing, cutting, and building the containment frame

### Jadyn:
* Documentation
* Project Coordinator

