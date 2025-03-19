# Raspberry Pi & Components

The purpose of this repository is to show the different components used in our Physical Computing class. These include a Raspberry Pi 4 4GB along with various components that assemble into a two-wheeled robot.

## The Raspberry Pi 4 Model B Board
<img width=600 src="https://github.com/bedrockskeleton/raspberry-pi/blob/main/RaspberryPiLabeled.png?raw=true">

CPU. The Raspberry Pi 4 B uses a Broadcom BCM2711 chip with 4 cores and a small integrated GPU. The chip is built on ARM architecture, which is known for running Android and Linux. In basic terms, the CPU is where our programs will run.

RAM. The Pi 4 can be configured with either 1, 2, 4, or 8 gigabytes of RAM. This one comes with a respectable 4 GB, useful for storing information that needs to be accessed quickly.

GPIO Pins. The General Purpose Input/Output pins are useful for interfacing with other electronics. By plugging in components like buttons and LEDs, you can interface with them using the Python or C programming languages. 

Ethernet. The Pi features an ethernet port capable of transfering 1 GB of data per second. This is useful if you want dependable, wired internet speeds, or if you want to give your Pi internet without configuring WiFi.

USB 3.0/2.0. Four USB ports are included on the Pi and are useful for connecting accesories like keyboards, mice, USB drives, and some sensors. Two of these four ports are USB 3.0, which allow faster data transfer speeds.

### Other Features
1. WiFi + Bluetooth Module. The Pi is capable of connecting to 5 GHz networks and can take advantage of Bluetooth 5. Both allow for fast connection to external devices.
2. DSI Display Port. This can be used to connect directly to external displays. To the left, you can also see the Micro SD card sticking out of the Pi. This is where the Operating System (OS) is flashed and also where data is permanently stored.
3. USB C Power Input. This port is the main way to power the Pi. It accepts 5 volts at 3 amps.
4. Micro HDMI Port. Primary method of connecting to external displays. The Pi 4 is capable of outputting to two 4k displays at once.
5. Secondary Micro HDMI Port.
6. CSI Camera Port. Where you can plug in external cameras like the Raspberry Pi Camera Module.
7. 3.5mm Audio Jack. The Pi can output sound from this port if an external speaker or wired headphones are connected.
8. USB Controller. Responsible for bridging the CPU to the 4 USB ports.
9. Ethernet Controller. Responsible for handling the data coming in and out of the ethernet port.

## Additional Accessories & Components

Along with the Pi itself, we'll also be using a bunch of components that take advantage of all the board's features. They're pictured below.

<img width=600 src="https://github.com/bedrockskeleton/raspberry-pi/blob/main/AccessoriesLabeled.png">

1. Lego Small Angular Motor. These motors will interface with the Build HAT to give our robot a way to move.
2. Breadboard & Electronic Components. We can build external circuits like the mock vending machine pictured to take full advantage of the Pi's GPIO pins.
3. Small Speaker. With no monitor connected, the Pi has no way to output sound. That is unless we use a small, 3.5mm-driven speaker as our audio output. This will allow our robot to make sounds based on conditions that we program.
4. Lego Technic Color Sensor. This is one method that our robot can use to "see" the world around it. The sensor connects to the Build HAT and outputs whatever color data depending on what it's looking at.
5. Ultrasonic Sensor. This sensor acts as a digital version of echolocation. It allows the Pi to reliably guage distances around it, depending on where the sensor is pointed. It connects via the Pi's GPIO pins.
6. Raspberry Pi Camera Module. This small camera taps into the CSI port and allows the Pi to perform basic image recogition. We can program our robot to perform certain actions based on what it sees using this.
7. Infared Sensor. This is like the sensor you see on the bottom of computer mice. It can report back basic color and distance information based on where it's pointed. I've used these types of sensors before to build line-following robots. These robots work by sweeping the sensor back-and-forth over a black line, guiding the robot back on track when the sensor sweeps off of the line.
8. Raspberry Pi Build HAT. This Hardware Attached on Top is used to connect a Pi to Lego Technic/Education sensors. It features a barrel-jack port so that you can provide the extra 8 volts required to run attached motors.
9. NeoPixel Stick. This small PCB features 8 RGB LEDs that we can use to make our robot more expressive.
10. Wiimote. This controller will be used to control our robot remotely. It features a gyroscopic sensor that we can use as another form of control for our robots.
11. GPIO Header Riser. This part will be sandwiched between our Raspberry Pi and Build HAT. The extra long pins can pop straight through the Build HAT, allowing us to access them even when the HAT is attached. This will allow us to connect things like our infared and ultrasonic sensors even when we're utilizing motors.

## Works Cited
Raspberry Pi Foundation. (2022, May 3). *Raspberry Pi Hardware*. Raspberry Pi. https://www.raspberrypi.com/documentation/computers/raspberry-pi.html

Timmons-Brown, D. (2019). *Learn robotics with Raspberry Pi: Build and code your own moving, sensing, thinking robots*. No Starch Press.
