
# Phone Controlled Robotic Arm
This project is a Robot Arm which can be controlled using an app on your phone that is created using MIT App Inventor. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| David Chang | Monta Vista Highschool | Mechanical Engineering | Incoming Junior

  
# Final Milestone



{:target="_blank" rel="noopener"}

# Second Milestone

My second milestone was creating the app on MIT App Inventor and using the slider on the app to send information onto the serial monitor on my computer.  So for this to work I swapped out the Arduino UNO with an ESP32 since the ESP32 has a built-in Bluetooth and wifi system, so it would be easier to work with than the Arduino Uno. On the MIT App Inventor, I used something called the Bluetooth client. The Bluetooth client is just the Bluetooth server where it will connect to a Bluetooth device when you need to. Other than the Bluetooth client that is in the app, there will be 4 sliders that will control the servos on the arm. 

For the coding portion on the MIT App Inventor website, I coded it so that whenever the connect button is pushed, there will be a list of Bluetooth devices that will show up for the user to choose from. Once they choose to connect to the ESP32, there will be a text on the app saying “connected”. There is also a button that is called disconnect, and that will disconnect you from the Bluetooth device you were connected to. For the serial monitor to receive inputs from the changes done in the app, the esp32 has to include a library that incorporates Bluetooth so that whatever is changed in the app, the ESP32 will receive. On the MIT App Inventor website, I coded it so that when the slider position changed, it will be sent to the ESP32 and will be printed onto the serial monitor.


[![David_BSE_Milestone2](https://res.cloudinary.com/marcomontalbano/image/upload/v1624650147/video_to_markdown/images/youtube--tUri4dxDE9c-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=tUri4dxDE9c "David_BSE_Milestone2"){:target="_blank" rel="noopener"}
![Screenshot (349)](https://user-images.githubusercontent.com/86091730/123485932-f91f9b00-d5bf-11eb-8547-b542401377aa.png){:target="_blank" rel="noopener"}
# First Milestone

My first milestone was building the robot arm and hooking up all the wires onto the breadboard and Arduino. On the Arduino, there would be one wire that goes into the ground power and one that goes into the 5 volts. On the other end of the wire, they will be connected to the breadboard. The 5 volts jumper will be connected to the positive column of the breadboard, while the ground power jumper will be connected to the negative side of the column. And to connect the servos there will be three wires, one will be connected to the same column as the ground power, one will be connected to the same column as the 5 volts wire, and one will connect from the servo directly to the Arduino digital port. I connected the wires to the PWM ports. What PWM ports do is that instead of turning the servo on and off, you will be able to control the degree the servos are turning to. 

I programmed the Arduino so that I can control the robot arm from the serial monitor of the application. I can control the servos separately on the serial monitor or control all of them at once.

[![David C Milestone 1](https://res.cloudinary.com/marcomontalbano/image/upload/v1624425325/video_to_markdown/images/youtube--ndd1jRbl1JI-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=ndd1jRbl1JI "David C Milestone 1"){:target="_blank" rel="noopener"}

![Screenshot (347)](https://user-images.githubusercontent.com/86091730/123485823-bf4e9480-d5bf-11eb-9392-426ffbe2dc1e.png){:target="_blank" rel="noopener"}
