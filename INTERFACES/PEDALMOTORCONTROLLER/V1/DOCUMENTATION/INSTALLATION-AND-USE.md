## Installation and Build Instructions

**This guide is only for those who want to make their own PMC.**
### Hardware

#### Fritzing Diagram
![Fritzing Diagram](../MEDIA-FILES/ASSETS/Diagram.png)
### Parts List

* Arduino GIGA R1 WiFi
* 4x 28BYJ-48 stepper motors
* 4x ULN2003 stepper motor drivers
* LCD1602 2x16 LCD display
* Joystick module
* Mini breadboard
* 3-pin potentiometer
* Jumper wires

#### Installation
1. Clone this repository to your machine.
2. In `src`, zip each folder into an individual file, EXCLUDING `src/Main`.
3. Install the [Arduino IDE](https://www.arduino.cc/en/software/) and launch. Under the Sketch tab, select `Include Library > Add .ZIP Library...`
4. Select and install each of the zipped folders you created in step 2.
5. Under the `Libraries` tab on the left (bookshelf icon), search and install `AccelStepper` and `arduino-timer`. These are external libraries that the PMC uses.
6. Once all zips are installed, make sure the program compiles by clicking the checkmark on the top left (labeled `Verify`).
7. Finally, connect an Arduino GIGA to your computer, select it in the top left, and select `Upload`.

### Usage

1. Remove the knob from the desired pedal parameter and attach a coupler to the exposed potentiometer
2. Download the [Serial Sensor](https://play.google.com/store/apps/details?id=com.karl.serialsensor) app on your phone
3. Turn on the PMC and connect to its WiFi access point on your phone (SSID and password are both "PedalMotorController")
4. In Serial Sensor, under the Sensors tab, select only **Gyroscope**
5. Under the Connection tab, select **Network** and input the IP address and port shown on the PMC's display
6. Press the play button in SerialSensor when you are ready to send data (you may need to do this twice for it to register)

