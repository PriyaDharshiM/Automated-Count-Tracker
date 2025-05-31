Automated Count Tracker:

Project Overview:
The Automated Count Tracker is a simple Arduino-based project designed to count the number of people entering a space. It uses an ultrasonic sensor to detect a person, a buzzer for sound notification, and a 16x2 LCD to display the current count. This project is useful for places like classrooms, buses, or events where monitoring the number of people is important.

Features:
1.Real-time person detection using an ultrasonic sensor.
2.Buzzer alerts when a person is detected.
3.Displays the total number of people on an LCD.
4.Prevents duplicate counting by resetting detection after each person.

Components Used:
1.Arduino Uno – 1
2.Ultrasonic Sensor (HC-SR04) – 1
3.Buzzer – 1
4.16x2 LCD Display – 1
5.Breadboard – 1
6.Jumper wires – As needed

Working Principle:
The ultrasonic sensor continuously checks the distance in front of it. When a person comes within 100 cm, it is detected. A buzzer beeps once and the person count is increased. When the person moves away, the sensor resets and waits for the next person. The count is shown on the LCD screen in real-time.

Connections:
1.Ultrasonic Sensor:
a.Trig → Pin 6
b.Echo → Pin 7

2.Buzzer:
a.Buzzer → Pin 8
b.LCD Display:
c.RS → Pin 12
d.EN → Pin 11
e.D4 → Pin 5
f.D5 → Pin 4
g.D6 → Pin 3
h.D7 → Pin 2

Tinkercad Stimulation:
https://www.tinkercad.com/things/8FnycQdlq2H/editel?sharecode=cRKmZHmYo9do66SFORGQPBw7AJn3bbnHtO43UCKY4qQ
[Click here to view my project in Tinkercad]

How to Use:
Connect the components as per the above wiring. Upload the Arduino code to your board. Power the Arduino using a USB cable or battery. As people walk past the sensor, the count will increase and display on the LCD.

Created By:
Priyadharshini M.
