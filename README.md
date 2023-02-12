# Minimal-GUI
A GUI for the 4x Parallel Arduino board
This is a GUI to control the 4x parallel arduino board.
The Control Arduino is pre programed and can not be altered or the board wont work.
When you power up the board there will be NO leds on. When you open the GUI and
choose the com chanel your board is pluged into it should lite up the White led.
Click on one of the 4 Arduinos and the corisponding color led should lite up.
Click on the Program button and you can now program the chosen Arduino.
Click the Arduino button and the GUI button should go gray, the Arduino led should
go off and the White led should go on. If you power down the board and power it up again
the White led will not go on till you select the com port on the GUI. If you select
program on you Arduino IDE when the White led in not on this will program the Control Arduino
and the board wont work. If you do this, to reprogram the Control Arduino power off and on
making shure the White led is OFF. The Arduino Control Program is Below. 
Copy and Paste it into your Arduino IDE. And download the program. Select the com port
and then select one of the 4 Arduinos and the board will work.

Control Arduino Program----------------------

[Arduino Command.zip](https://github.com/moose314/Minimal-GUI/files/10716162/Arduino.Command.zip)
