# Cybersecurity 150 Lab

## Name of Project
ESP32: Messages to WhatsApp

## Purpose
To send messages from the ESP32 to send messages to WhatsApp using CallMeBot

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Link to Documentation Followed
https://randomnerdtutorials.com/esp32-send-messages-whatsapp/

##### Youtube Video 1: 
https://youtu.be/1CWIgxkviuU?si=6GBiBNNN7kArHcJM

## Steps I followed
1.	Add Phone Number to Contacts:
Open your phone's contacts.
Add the phone number +34 621 331 709, naming it as desired. (Ensure accuracy by cross-checking on the CallMeBot website.)

2.	Send Authorization Message:
Open WhatsApp on your phone.
Find the newly added contact.
Send the message: "I allow callmebot to send me messages" to the contact.

3.	Wait for API Activation:
Keep an eye on your WhatsApp for a message from the bot.
Wait until you receive the message: "API Activated for your phone number. Your APIKEY is XXXXXX" from the bot.

4.	Prepare ESP32 Code:
Open the Arduino IDE.
Go to Sketch > Include Library > Manage Libraries.
Search for URLEncode library by Masayuki Sugahara and install it.

5.	Upload Example Code to ESP32:
Insert your network credentials, phone number, and API key into the example code.
Upload the modified code to your ESP32 board.

6.	Test ESP32 Connection:
Open the Serial Monitor in the Arduino IDE.
Set the baud rate to 115200.
Press the reset (RST) button on the ESP32 board.
Observe the Serial Monitor for successful network connection and message sending confirmation.

## ScreenShots of completed project

![ESP32 1](https://github.com/Anthe1/CSN150-Documentation-Template/assets/134184529/5578d888-be77-457a-b960-e40b8b03063a)


