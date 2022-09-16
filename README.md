# Purpose

The following tutorial will get you up and running to build an RC car with the provided materials. All of the soldering is already done and the code is flashed onto the brain board. It will be your responsibility to use the tools provided to you in your orientation bag along with the tools available in the Makerspace to design and build a chassis for your car.

### Bill of Materials

![](/assets/readme/brain_board.jpeg)
  _1 brain board with Arduino Nano and battery connector_
![](/assets/readme/battery.jpeg)
  _1 9v battery_
- 1 motor board
- 2 gear motors
- 1 Bluetooth module (HC-05 or 06)
- 2 tires

# Electronics Assembly

1. Collect the above components from the Prototyping Labs staff.

1. You want to stack the **motor board** on top of the **brain board**. To indicate it's stacked properly, ensure that the rounded corners of the board and pins are aligned.

1. Connect the **2 gear motors** to the motor driver. The motor driver has screw terminals (green) where you can attach the pins. Either a Phillips-head or flat-head screwdriver will work. You may need to flip these at a later step if your car is going the wrong direction.

1. Stack the **Bluetooth board** on top of the **motor board**. Make sure the rounded corners and pins are aligned.

1. Design and build the body of the RC car, you are welcome to use the materials provided in the Prototyping Labs from cardboard to wood. Make sure it holds everything! If you do decide to use the MDF, Birch, or Acrylic make sure you have done your [first laser cut tutorial](https://gixlabs.github.io/how_to/first_lasercut.html) before using any of the laser cutters.

6. Glue on the gear motors to the body of the RC car that you have designed/built and assemble the tires.

7. After you connect the 9V battery, LEDs should light up on the brain board and Bluetooth board. If it doesn't turn on then the battery connector may not be connected properly or the 9v battery is dead. Check both!

# Connecting to Bluetooth

1. If you have an Android phone, go to the play store and install [Bluetooth RC car](https://play.google.com/store/apps/details?id=braulio.calle.bluetoothRCcontroller&hl=en_US&gl=US). _If you do not have an Android phone we have a controller that you can use to connect to the RC car._

2. Once the app has installed, go to your Bluetooth and connect to the RC car (whatever the Bluetooth name is for the device) once you have successfully connected, open the app (Bluetooth RC car) and connect to the Bluetooth device again. _If you are using the remote controller you should already be connected to the RC car._

NOTE: If you connect to the RC Car using your android phone and it ask for a password, the default password is 1234.

# Debugging Motors
If you have been able to connect to your RC car, but it is going the wrong direction, you may need to swap the motor wires.
- If your car is going backward when it should be going forward - Swap the red and black wires on both motors.
- If your car is going left when it should be going right or right when it should be going left - Swap which side of the motor driver your motors are wired to.
- For other problems, ask a member of the Prototyping Labs staff.

### Congratulations you are now connected to the RC car! Happy racing! 🏁🏎

To change the speed of the RC car, you'll need to learn how to flash code to the RC car [here](https://github.com/GIXLabs/rccars/blob/main/tutorials/flash_code.md).

# If you want to solder
**IF** you want to solder gather all the components and look at an example to ensure the components are properly placed:

- The Arduino Nano and the 9v battery connector to the **brain board**
- The motor driver to the **motor board**
- The Bluetooth module, resistors, and capacitor to the **Bluetooth board**
