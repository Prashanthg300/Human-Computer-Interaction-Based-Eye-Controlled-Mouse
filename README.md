# Human Computer Interaction Based Eye Controlled Mouse

## Table of Contents
- [Introduction](#introduction)
- [Aim and Objective](#aim-and-objective)
- [Scope of the Project](#scope-of-the-project)
- [Motivation](#motivation)
- [Problem Statement](#problem-statement)
- [Proposed System](#proposed-system)
- [Technologies and Libraries Used](#technologies-and-libraries-used)
- [Installation](#installation)
- [Usage](#usage)
- [Output Screenshots](#output-screenshots)
- [Contributors](#contributors)
- [License](#license)

## Introduction
Eye tracking technology has been a fundamental tool in fields such as psychology, marketing, and user interface design. Our project leverages this technology to help individuals with physical disabilities operate a computer using their eye movements. The eye-controlled mouse provides a natural and efficient means of interaction, enhancing accessibility and usability.

## Aim and Objective
The primary objective of this project is to develop a system that allows users to control the mouse cursor using their eyes. This system is particularly beneficial for amputees and individuals with motor disabilities. The specific objectives include:
- Detecting face and eyes
- Extracting eye corners
- Developing an algorithm to calculate the point of gaze
- Creating a user-friendly GUI
- Implementing a simple calibration technique

## Scope of the Project
This project aims to enhance the independence and productivity of individuals with physical disabilities by providing them with a tool to interact with computers using eye movements. The benefits include:
- Easier computer control
- Assisting disabled and handicapped individuals in using computers
- Potential use in interactive games and advertisements

## Motivation
The motivation behind this project is to offer a natural and efficient method of computer interaction for users, particularly those with physical limitations. By using eye-tracking technology, we aim to bridge accessibility gaps and revolutionize human-computer interaction.

## Problem Statement
Existing systems for cursor control typically require manual input through a mouse or touchpad, which can be challenging for individuals with physical disabilities. This project proposes an eye-tracking-based control system that enhances usability and accessibility by allowing users to control the cursor through eye movements.

## Proposed System
Our proposed system integrates eye-tracking technology with human-computer interaction principles to create a user-friendly interface for controlling the mouse cursor. The system uses a specialized video camera to track eye movements and translate them into cursor movements on the screen.

## Technologies and Libraries Used
- **OpenCV**: For computer vision tasks and image processing
- **Dlib**: For detecting facial landmarks
- **Imutils**: For image processing convenience functions
- **PyAutoGUI**: For controlling the mouse and keyboard
- **NumPy**: For numerical operations
- **Python**: The programming language used for implementation

## Installation
To install and run the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/eye-controlled-mouse.git
    cd eye-controlled-mouse
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:
    ```bash
    python main.py
    ```

## Usage
Once the application is running, follow the on-screen instructions to calibrate the eye tracker. Use the detected eye movements to control the mouse cursor. The application supports basic mouse functions like moving the cursor, left click, right click, and scrolling.

## Output Screenshots

Below are some screenshots demonstrating the key functionalities of the project:

- **Activating Mouse**
  ![Activating Mouse](Screenshots/Activating%20mouse.png)

- **Mapped to Mouse Cursor**
  ![Mapped to Mouse Cursor](Screenshots/Activated%20mouse.png)

- **Moving Mouse Pointer Right**
  ![Moving Mouse Pointer Right](Screenshots/Right%20cursor%20movement.png)

- **Left Click**
  ![Left Click](Screenshots/Left%20click.png)

- **Right Click**
  ![Right Click](Screenshots/Right%20click.png)

## Contributors
- **Prashanth G** 
- **Kodi Raju** 
- **P. Laxmi Sruthi** 
- **T. Pranitha** 

## License
This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details.
