# Networking-Fundamentals
This repository provides an overview of the fundamentals of computer networking. After completing Adrian Cantrill's Networking Fundamentals course, I created a brief summary of each layer of the OSI Model, along with questions to reinforce key concepts. 

## Layer 1 Physical 
The Physical Layer is the first layer of the OSI model, and it’s all about how data is physically transmitted and received over a network. This layer sets the hardware standards like voltage levels, timing, data rates, distances, and connectors

**What is Layer 1 in networking?**

Layer 1 is the Physical Layer in networking, which involves transmitting and receiving raw bit streams between a device and a shared physical medium.

 **What are the types of physical mediums used in Layer 1?**

The physical mediums used in Layer 1 can be copper (electrical), fiber (light), or Wi-Fi (radio frequency).

**What is a hub in the context of Layer 1 networking?**

A hub is a device that retransmits anything it receives on any of its ports to all other ports, including errors or collisions. It creates a shared medium for all connected devices.

**What are some limitations of Layer 1?**

 Some limitations of Layer 1 include:

1. No individual device addresses.
2. Unable to detect collisions.
3. No media access control.
4. No intelligence or methods to control transmission.

**What happens when a collision occurs in Layer 1?**

 When a collision occurs in Layer 1, multiple devices transmit simultaneously, making all the transmitted information useless. Layer 1 can't detect collisions.

**Why is Layer 2 necessary for Layer 1 to be useful?**

 Layer 2, the Data Link Layer, is necessary because Layer 1 lacks device addresses, collision detection, media access control, and intelligent communication methods.
