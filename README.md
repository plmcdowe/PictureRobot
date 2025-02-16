# Picture Robot
### An Arduino robot controlled through Python to copy physical photographs with a DSLR camera.   
>> The Arduino Uno + Adafruit Motor Shield drives:   
>> \> Six, 5v 28BYJ-48 stepper motors   
>> \> One, 12v vacuum pump   
>> \> One, HC-SR04 sonar sensor   
>> \> One, MMA8452 accelerometer   
>> \> Triggers a Nikon DLSR through a hacked-up MC-DC2 Remote Release Cord   
>>    
> [ Robot_GUI.py ](https://github.com/plmcdowe/PictureRobot/blob/0e17b5465a513a3238d006e566289306773ff45b/Robot_GUI.py) provides control over serial through a Tkinter GUI.   
> [ TkinterRobot.ino ](https://github.com/plmcdowe/PictureRobot/blob/0e17b5465a513a3238d006e566289306773ff45b/TkinterRobot.ino) is the Arduino program to drive the hardware.   

Demo of the python GUI interacting over serial with the Arduino to turn on a blue LED:   

https://github.com/user-attachments/assets/d8e87a40-d99c-4695-b16d-e683b1de0d4c
