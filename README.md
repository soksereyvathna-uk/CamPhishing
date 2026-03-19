### Please use this tool for education purpose only
CamPhish: An Educational Overview
Abstract

CamPhish is a proof-of-concept tool designed to demonstrate how web-based camera access permissions can be exploited during penetration testing scenarios. The tool operates by hosting a web page that requests camera access from a target device. If permission is granted, images captured from the device’s camera are transmitted to the hosting server. This project is intended strictly for educational and ethical cybersecurity research purposes.

1. Introduction

CamPhish illustrates a social engineering–based technique in which a target is encouraged to grant camera access through a seemingly legitimate web interface. The tool highlights the importance of user awareness, browser security permissions, and ethical considerations in cybersecurity. It is commonly referenced in penetration testing environments to study human factors and client-side security vulnerabilities.

2. System Description

CamPhish hosts a web application using a built-in PHP server and exposes it to the internet via tunneling services. The generated link is shared with a target user. When accessed, the web page prompts the user to allow camera access. Upon approval, the system captures images from the device’s front camera or webcam.

To improve user engagement and increase interaction time, the tool provides predefined web templates that simulate legitimate content.

3. Features

The tool includes the following functionalities:

Automated web page templates to maintain user interaction

Simulated festival greeting pages

Embedded live-stream-style video pages (e.g., YouTube-based layouts)

Simple input mechanisms such as festival names or video identifiers

These features are intended to demonstrate how social engineering techniques can be combined with technical methods in security testing.

4. Supported Platforms

CamPhish has been tested on multiple operating systems commonly used in security research, including:

Kali Linux

Termux (Android environment)

macOS

Ubuntu

Parrot Security OS

5. Installation Requirements

The tool requires the following software components:

PHP (for the local web server)

SSH or tunneling services for remote access

Git and supporting utilities

Required dependencies can be installed using the system package manager.

6. Ethical Considerations

CamPhish is developed solely for academic learning, penetration testing demonstrations, and cybersecurity awareness training. Unauthorized surveillance, privacy invasion, or misuse of this tool is unethical and may be illegal. Users are responsible for ensuring that all testing is conducted with explicit permission and within legal boundaries.

7. Acknowledgements

This project was inspired by earlier cybersecurity research tools developed within the open-source community. Credit is given to prior contributors whose work supported the educational foundation of this project.
