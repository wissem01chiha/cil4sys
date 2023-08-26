##  Car Licencing Plate Detection and Recognition  Embedded Software for Intelligent Parking Systems.




### Table of Contents

- [LPDR Embedded Software](#project-name)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Features](#features)
  - [Installation][installation]
  - [Usage](#usage)
  - [Documentation](#documentation)
  - [Contributing](##contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgments](#acknowledgments)

### Description 
LPDR (License Plate Detection and Registration) is an automated application designed to identify and register car license plates within parking areas.  

 The primary function of LPDR involves the detection of license plates, which are subsequently recorded for billing purposes.  
This application employs a multi-stage approach, utilizing both video and image processing techniques, to accurately extract 

Tunisian license plate numbers. However, it's important to note that the current version of LPDR is limited to recognizing numerical characters on license plates and does not have the capability to read non-numerical characters. 
### Features 
- Processing of video records  from the parking camera
- License Plate Detection: Utilizes computer vision techniques to accurately locate license plates in various conditions.
- Optical Character Recognition (OCR): Recognizes alphanumeric characters on license plates, converting visual data to readable text.



###  Installation

Update package information and upgrade installed packages

        sudo apt update
        sudo apt upgrade

Upgrade Python packages: pip, setuptools, and wheel

        pip install --upgrade pip setuptools wheel

Install library dependencies 

    sudo apt install python3-opencv libopencv-dev

clone to the repository 

    git clone https://github.com/wissem01chiha/cil4sys

Navigate to the repository's dist folder and run 

    pip3  install ./dist/cil4sys-0.1.tar.gz

This will install the application with it dependencies and data files.  

Verify the installation 

    cil4sys --version


### Usage

connect your camera to raspberry pi board throgh the USB port or the default raspi port , only one camera wich is ste to default will be detected  for the raspi kit camera you miust enable the camera interface 

after installation 
 
### Documentation 

<img src="doc/wiring.png" alt="Local Image" width="350" height="350">




### Contributing 
### License
this is under 
### Contact
### Acknowledgments









 










 

[installation]: #installation