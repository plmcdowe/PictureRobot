# Picture Robot
#### An Arduino robot controlled through Python to copy physical photographs with a DSLR camera.    
It ran surprisingly well for how hacked together it was. But, it never did copy a photo on its own.      
Despite this, the project was a lot of fun - pushing the limits of what I could do as cheaply as possible.    
> The Arduino Uno + Adafruit Motor Shield drives:   
>> \> Six, 5v 28BYJ-48 stepper motors - left/right movement of the body and up/down of the arm.    
>> \> One, 12v vacuum pump - attached to a rubber hose running to a suction cup at the end of the arm.       
>> \> One, HC-SR04 sonar sensor - stopped the end of the arm on a photo to be lifted.   
>> \> One, MMA8452 accelerometer - kept the end of the arm level throughout movement.    
>> \> One, 12v push pull solenoid - flick the photo off the suction cup.  
>> \> Triggers a Nikon DLSR through a hacked-up MC-DC2 Remote Release Cord   
>>
I wish that I had better documented the project as I went, wiring diagrams in particular.       
I sketched much of it by hand in a long since lost notebook.     
If time allows, I may revisit parts of the project and document those more thoroughly.        
### [ Robot_GUI.py ](https://github.com/plmcdowe/PictureRobot/blob/0e17b5465a513a3238d006e566289306773ff45b/Robot_GUI.py) provides control over serial through a Tkinter GUI.   
### [ TkinterRobot.ino ](https://github.com/plmcdowe/PictureRobot/blob/0e17b5465a513a3238d006e566289306773ff45b/TkinterRobot.ino) is the Arduino program to drive the hardware.   


### Demo of the python GUI interacting over serial with the Arduino to turn on a blue LED:   

https://github.com/user-attachments/assets/cacfdb74-5041-498e-838f-d35403442f15    

![20250420_195659](https://github.com/user-attachments/assets/febc1436-6690-4107-b193-1d74bc4ac559)
