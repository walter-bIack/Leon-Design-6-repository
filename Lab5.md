# **Lab 5**
## Leon Selyomin
### I pledge my honor that I have abided by the stevens honor system - *Leon Selyomin*

**Description:** For this lab, we were tasked with using Paho-MQTT, which is a protocol that allows publishing and subscribing between modules

pip install paho-mqtt
--
Install the Paho MQTT library using pip

![Screenshot 2025-05-09 010615](https://github.com/user-attachments/assets/1479087e-5958-49d8-8b8a-18043a449d0b)

git pull
--
Update the repository with git pull

![Screenshot 2025-05-09 011727](https://github.com/user-attachments/assets/ebb534d3-ebe6-4113-9453-5ab430a45ebc)


Run subcpu.py in one terminal
--
This is the subsciber

![Screenshot 2025-05-09 012244](https://github.com/user-attachments/assets/af59076f-32fa-45cf-be19-c71abc29ceb7)


Run pubcpu.py in another terminal
--
This is the publisher

![Screenshot 2025-05-09 012258](https://github.com/user-attachments/assets/96e18950-f8aa-42d8-8e8f-499b29249908)

Explaination of what is going on 
--
The pubcpu.py and subcpu.py scripts demonstrate a basic IoT communication setup. The pubcpu.py script acts as a publisher, collecting CPU usage data and sending it to a topic, while subcpu.py acts as a subscriber, listening to that topic and printing any incoming messages. Together, they simulate how devices in an IoT network exchange data in real time through a messaging protocol.

