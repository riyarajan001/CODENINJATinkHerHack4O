<p align="center"> <img src="./img.png" alt="Project Banner" width="100%"> </p>
Smart Doorbell System 🎯
Basic Details
Team Name: TinkerHub Innovators
Team Members

Member 1: Riya Rajan - MES ASMABI COLLEGE

Member 2: Aiswarya C R - ICCS COLLEGE of ENGINEERING AND MANAGEMENT COLLEGE

Hosted Project Link

(https://github.com/riyarajan001/CODE-NINJA-Tink-Her-Hack-4.O)

Project Description

A smart doorbell system that detects familiar and unfamiliar faces at the door, sending real-time alerts to the homeowner through a mobile/web interface.

The Problem statement

Traditional doorbells provide no information about who is at the door, causing security risks and missed visits.

The Solution

We built a camera-enabled doorbell with facial recognition to identify visitors, alert users immediately, and store visitor history for future reference.

Technical Details
Technologies/Components Used

For Software:

Languages used: Python, JavaScript

Frameworks used: Django (Backend), Flutter (Frontend)

Libraries used: OpenCV, face_recognition, numpy, pandas

Tools used: VS Code, Git, Docker

For Hardware:

Main components: Raspberry Pi 4, Camera Module, Push Button, LEDs

Specifications: Raspberry Pi 4, 8MP Camera Module, Wi-Fi enabled

Tools required: Breadboard, Jumper Wires, Power Supply

Features

Real-time face detection and recognition

Instant SMS, App, and Email alerts for unfamiliar visitors

Local database of familiar faces for automatic identification

Web dashboard to monitor and review visitor history

Implementation
For Software:
Installation
pip install -r requirements.txt
Run
python manage.py runserver
For Hardware:
Components Required

Raspberry Pi 4

Camera Module (8MP)

Push Button for doorbell

LEDs

Breadboard & Jumper wires

Power supply

Circuit Setup

Connect the camera module to the Raspberry Pi.

Connect the push button to GPIO pins.

Connect LEDs for visual notifications via resistors to GPIO pins.

Power the Raspberry Pi and run the backend software.

Project Documentation
For Software:
Screenshots


Dashboard showing visitor notifications


Real-time alert for an unfamiliar visitor


Visitor history log with timestamps and photos

Diagrams

System Architecture:


Camera captures images → Backend processes → Sends alerts → Frontend dashboard displays results

Application Workflow:


User receives alert, checks live feed, and reviews visitor history

For Hardware:
Schematic & Circuit


Connections of camera, button, and LEDs to Raspberry Pi


Visual schematic of hardware setup

Build Photos


Team working on the project setup


All components laid out


Assembling camera and LED circuit


Completed smart doorbell ready for deployment

Additional Documentation
For Web Projects with Backend:
API Documentation

Base URL: https://api.smartdoorbell.com

Endpoints

GET /api/visitors

Description: Retrieves list of recent visitors

Parameters: None

Response:

{
  "status": "success",
  "data": []
}

POST /api/alert

Description: Sends alert for a new visitor

Request Body:

{
  "name": "Unknown",
  "image": "base64string"
}

Response:

{
  "status": "success",
  "message": "Alert sent"
}
For Mobile Apps:
App Flow Diagram


User receives alerts, views live feed, and checks visitor history

Installation Guide

For Android (APK):

Download the APK from [Release Link]

Enable "Install from Unknown Sources" in device settings

Open the APK and follow installation prompts

Building from Source:

# For Android
flutter build apk
# For iOS
flutter build ios
For Hardware Projects:
Bill of Materials (BOM)
Component	Quantity	Specifications	Price	Link/Source
Raspberry Pi 4	1	4GB RAM, Wi-Fi	₹4500	[Link]
Camera Module	1	8MP, 1080p	₹900	[Link]
Push Button	1	Standard	₹50	[Link]
LEDs	5	Red, 5mm, 20mA	₹5 each	[Link]
Breadboard	1	830 points	₹100	[Link]
Jumper Wires	20	Male-to-Male	₹50	[Link]

Total Estimated Cost: ₹5600

Assembly Instructions

Step 1: Prepare Components
Gather all components and check specifications


All components laid out

Step 2: Build the Power Supply
Connect Raspberry Pi 5V to breadboard positive rail and GND to negative rail


Power connections completed

Step 3: Add Components
Connect push button, LEDs via resistors, and camera module


Circuit assembled

Final Assembly:


Completed project ready for testing

For Scripts/CLI Tools:

Basic Usage:

python script.py [options] [arguments]

Examples:

python script.py input.txt
python script.py -v input.txt
python script.py -o output.txt input.txt
python script.py -c config.json --verbose input.txt
Project Demo
Video

[Add your demo video link here]
Shows live face detection, alert notifications, and dashboard usage

AI Tools Used

Tool Used: ChatGPT, OpenCV
Purpose: Assisted in code generation, debugging, and image processing integration
Percentage of AI-generated code: ~20%
Human Contributions: Architecture design, hardware setup, backend logic, frontend dashboard, testing

Team Contributions

Riya Rajan: Backend development, API integration, Hardware setup

Aiswarya C R: Frontend design, UI/UX, Testing, Documentation
