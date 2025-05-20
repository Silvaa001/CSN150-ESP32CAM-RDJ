# Cybersecurity : CSN150-ESP32 Camera SetUp

## Name of Project
ESP32 Camera SetUp

## Purpose
Set up ESP32 and Arduino enviornment. Execute sketch " Wifiscanner". 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation

##### Video 1: 

##### Other Links: 


## Steps I followed
1. File > Examples > ESP32 > Camera > CameraWebServer.
2. Switched to AI-THINKER model 
3. Connected ESP32 to my network
4. Copied and pasted IP to my browser to gain access to camera.

## Problems
Note your problems or errors here.  Google any error you may come across, and not what you tried (even if it does not work), and what was the final answer. Document your errors and solutions that worked for you.  

1. NO ISSUES WERE ENCOUNTERED!! 

### Example Problem
1. Arduino code will not load on ESP32 Cam.
   Answer: Camera drivers were incorrect I needed to install the driver: [https://www.wch-ic.com/downloads/CH341SER_ZIP.html](https://github.com/martin-ger/esp32_nat_router).  I used file, "CH341SER.ZIP" and it worked.

## ESP32 WiFi Scan Assignment:

## Steps I Followed:

1. Select AI Thinker ESP32 board and the port.
2. File>Examples>Wifi>WifiScan
3. Choosing 115200 baud rate

## CSN 150 Final Project - ESP32 Whatsapp messages

## Steps I Followed:

1. Add the phone number +34 621 331 709 to your Phone Contacts on Whatsapp.
2. Send the following message: “I allow callmebot to send me messages” to the new Contact created.
3. Wait until you receive the message “API Activated for your phone number.
4. Installing the URLEncode Library on ARDUINO
5. Selecting AI Thinker ESP32 board with appropriate port.
6. Pasting code and fill in the missing user credentials.
7. wait for message sent in serial monitor.

## Problems:

Serial Monitor did not want to connect and send the message. To resolve, I noticed I was connected to the wrong WiFi.

## Final Report
