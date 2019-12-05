# Group4_Project_2019
IB Group 4 project for the POHS computer science class of 2019

## **Project Description:**

  Our Group 4 project was to link an LED board to a school twitter account to relay announcements to the student body. For this project, we used various libraries to aid us in developing our code as well as relying on code examples from projects similar to ours. This project required us to work together to pull tweets from the internet, program, and wire the LED board, as well as build a containment unit.

## **Materials necessary:**
* Raspberry Pi 3

* Flexible Adafruit DotStar Matrix 8x32 - 256 RGB LED Pixels

* Wood or acrylic (optional for containment unit)

## **Containment Unit Building Instructions**
Once all pieces are all cut out, follow these steps. Read all instruction steps before proceeding.

1. Glue the DotStar Matrix to the 4" x 13" board, ensuring that the wires are coming through the rectangular hole.

2. Take the 1.5” x 3.25” inch rectangle and glue it to a 1.5” x 3.75” rectangle with no holes, with the bottom edges flush together and the side edges flush together. 

3. Glue the 1.5” x 3.75” rectangle with no holes to another 1.5” x 3.75” rectangle with no holes, all edges flush together.

3. Glue another 1.5” x 3.75” rectangle with a rounded rectangular hole in the middle to the previous 1.5” x 3.75” rectangle with no holes. You should now have a four-piece tall rectangular prism.

4. Glue another  1.5” x 3.75” rectangle with a rounded rectangular hole in the middle to another 1.5” x 3.75” rectangle with a rounded rectangular hole in the middle. All edges must be flush to one another. You should now have a five-piece tall rectangular prism.

5. Glue the  1.5” x 3.75” rectangle with a keyhole shape to the top rectangle with the rounded rectangular hole. You should now have a 6-piece tall rectangle with a notch cut out of a bottom edge.

6. Take the remaining 6 pieces and repeat steps 2-5, doing step 2 twice in lieu of step 1. 

7. Once the second stack has been completed, you should have two 6-piece high rectangular prisms, one with a small chunk missing from a bottom edge.

8. Glue both pieces straightly to the back of the 4" x 13" rectangle, ensuring that you are not covering the rectangular hole. Ensure that you can see the keyholes and that the circular hole in the keyhole is below the long hole. The rectangular prism missing a bottom edge must be placed to the right of the rectangular hole, with the missing edge facing the bottom of the board.

## **Raspberry Pi 3 GPIO Pins**
![Pins]
(https://raw.githubusercontent.com/JadynCleary/Group4_Project_2019/master/pi3_gpio.png)

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
* Documenting the project

