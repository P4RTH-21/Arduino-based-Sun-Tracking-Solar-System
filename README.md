Sun-Tracking Solar System

A microcontroller-based project where a solar panel automatically rotates toward the sun using LDR sensors and a servo motor. The system stores solar energy and powers a small bulb/LED.

⭐ Project Summary

This project tracks sunlight in real time using two LDR sensors placed on either side of the panel. Depending on which LDR receives more light, the Arduino rotates the servo to align the solar panel with maximum sunlight. The stored power is then used to glow a bulb.

This project demonstrates:

Basic robotics using Arduino

Light sensing using LDRs

Servo motor control

Solar power storage

Small-scale automation

🔧 Components Used

Arduino UNO

Small Solar Panel (3–6V)

SG90 Servo Motor

2 × LDR Sensors

2 × 10kΩ Resistors (LDR voltage divider)

Breadboard

Jumper wires (male–male & male–female)

9V Battery + Battery Clip

Power Jack

LED/Bulb

Transistor or MOSFET (for bulb control)

USB Cable (programming Arduino)

⚡ How the System Works

The two LDR sensors continuously measure sunlight intensity on both sides of the panel.

The Arduino compares both values and rotates the servo toward the brighter side.

As sunlight shifts during the day, the servo keeps adjusting the panel to face the strongest light.

This helps capture maximum solar energy, which is then stored and used to power a bulb or LED.

📸 Project Image

![WhatsApp Image 2025-11-23 at 18 50 13_b630fd33](https://github.com/user-attachments/assets/37cab9dd-71e1-4aef-af7b-5f62d1799631)

![WhatsApp Image 2025-11-23 at 18 50 12_204568bd](https://github.com/user-attachments/assets/96103be5-6d82-4c1d-8af5-98fcb97e98e0)

![WhatsApp Image 2025-11-23 at 18 50 14_a16fbb93](https://github.com/user-attachments/assets/4228ab60-7965-4338-ae49-9ec48f8e4bf0)

![WhatsApp Image 2025-11-23 at 18 50 12_6c0c5968](https://github.com/user-attachments/assets/84ae528b-2456-4629-8b50-627952d7d7ad)

![WhatsApp Image 2025-11-23 at 18 50 14_62f594e0](https://github.com/user-attachments/assets/884e1f73-c01d-449f-9c8e-45d76bcc8d58)

![WhatsApp Image 2025-11-23 at 18 50 14_10866dd9](https://github.com/user-attachments/assets/9949bfd7-9efb-48bd-a6a4-ce52e9aacfe3)

![WhatsApp Image 2025-11-23 at 18 50 13_fe8fd641](https://github.com/user-attachments/assets/ef9374d0-3357-4ac5-b893-4600aa8edc37)
