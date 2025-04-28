YouTube Demo Videos: https://www.youtube.com/playlist?list=PLQ-1B-UMBFj7BbOCyPhqwsLzQJ6LzSdxZ

Install one pf these program onto the Arduino. There are many concepts to do - larger programs and concepts are easier to split up. The are images to help guide the users in FinalSubmissionPictures_PeterVaughanv folder.

You can use the serial monitor in the Arduino IDE to keep track of the print lines and sent lines to the Arduino. Otherwise, you can use a RS232 attachment and use PuTTy or equivalent. You will need to adjust settings.

Personal preference for Putty setup:
- Connection type to "Serial" at the programmed baud speed rate. In my example, it is 9600. Typically, it will default to 9600.
	Adjust the COM1 to the correct COM Port. If you are unsure, you can go to the Arduino IDE to find out what COM Ports are active.
- If you adjust the program to take input, this step is important to do. Otherwise, you can skip this step.
	Click "Terminal" and check the box for "Implicit CR in every LF". Also, "Force on" the "Local echo". 
- Adjust "The Function keys and keypad" under "Keyboard" to Linux. Otherwise, you may get a strange output.
- Click on "Open" to start the program. 

![PuTTY 1](https://github.com/user-attachments/assets/faaa7bea-e0b8-43be-abb8-0c440b5cbf91)

![PuTTY 2](https://github.com/user-attachments/assets/d86b8f8e-2710-4e24-a89c-5f111f6f518e)

![PuTTY 3](https://github.com/user-attachments/assets/7e1e7400-85c7-4b26-9c0e-23e2db22784d)


Other files are connect to the main INO File for a working program.
