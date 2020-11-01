## **Home Automation**

This project utilizes multiple devices and sensors such as:
 - Raspbery PI 3/4
 - Jetson TX2 / Xavier
 - Microsoft Kinect v2
 - Microphones
 - Smoke detectors
 - Water Leakage Sensor
 
 
### Architecture
Microservice design containing:
- Web page 
- Main service module - KCM
- Database - Postgres
- Communication broker - RabbitMQ
- 4 additional microservices related to data/commands processing 
- 13 microservices to run on the end point devices 
Architecture design is [here](https://github.com/petarnikolovprojects/vehicles_pedestrian_tracking) and the services description is [here](https://github.com/petarnikolovprojects/HomeAutomation/blob/master/Karoli_services_description.txt)


### Technologies used:
- Languages
	Python, C#
- Database
	Postgres, ES
- Communication
	RabbitMQ, TCP/IP
- Web
	Flask, html, css
- Libraries
	OpenCV, EmguCV, scikit-learn, keras, tensorflow
- Computer vision
	Object detection / classification, people detection and tracking, activity recognition
- Speech recognition
	Voice/Keyword recognition, 
- NLP 
	Topic understanding, filtering
	
