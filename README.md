🆘 RescueTouch – Emergency Communication System for Deaf-Blind Individuals
📘 Overview

RescueTouch is a two-board embedded system designed to help Deaf-Blind individuals send rapid emergency alerts to responders or caregivers. Developed as a fully functional hardware prototype, the device combines tactile input, visual output, and microcontroller communication to provide a fast, accessible signaling system in critical situations.

This project was completed as part of a multidisciplinary design initiative to address real-world accessibility challenges through embedded electronics and user-centric hardware design.
🔧 Tools & Technologies

    KiCad – PCB schematic design and layout

    STM32CubeIDE (C++) – Microcontroller programming and peripheral configuration

    Onshape – CAD modeling for 3D-printed housing

    3D Printing – Custom enclosures for usability and durability

    UART Serial Communication – Inter-board data exchange

    Breadboarding & Testing – Prototype validation

⚙️ System Architecture

    Board 1 (User Device):

        Braille-labeled physical buttons

        STM32F0 microcontroller

        Sends predefined emergency signals via UART

    Board 2 (Responder Display):

        LCD display

        STM32F0 microcontroller

        Receives and interprets signal

        Displays emergency message (e.g., “NEED HELP”)

    Communication Protocol:

        Serial data transmission using UART

        Custom signal encoding and debouncing logic for input reliability

🧠 Key Contributions

    Designed and implemented custom schematics using KiCad

    Programmed STM32 microcontrollers in C++, enabling reliable two-way communication between boards

    Created a 30-page technical design document detailing system architecture, emergency use cases, signal reliability testing, and human-centered design principles

    Modeled and printed custom 3D housing using Onshape, ensuring tactile accessibility and protective durability

    Verified full system functionality through iterative testing, soldering, and breadboarding

    📌 Future Improvements

    Add haptic feedback motor or LED indicators for multi-sensory feedback

    Expand message set with Morse-code-like input

    Implement wireless protocol (e.g., BLE or LoRa) for long-range alerts

🙋‍♂️ About the Developer

I’m Kaviyan Jeyakumar, a junior Electrical Engineering student at the University of Waterloo. I’m passionate about designing hardware systems that merge technical performance with human impact. If you’re working on accessibility-focused devices or embedded systems, I’d love to connect!

📫 kaviyan.n.jeyakumar@gmail.ca
