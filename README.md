# Human Computer Interaction Based Eye Controlled Mouse

![Project Banner](Screenshots/1%20Home%20Page.png)

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

- **Home Page**
  ![Home Page](Screenshots/1%20Home%20Page.png)

- **Detecting Face**
  ![Detecting Face](Screenshots/2%20Detecting%20Face.png)

- **Activating Mouse**
  ![Activating Mouse](Screenshots/3%20Activating%20Mouse.png)

- **Mapped to Mouse Cursor**
  ![Mapped to Mouse Cursor](Screenshots/4%20Mapped%20to%20Mouse%20Cursor.png)

- **Moving Mouse Pointer Right**
  ![Moving Mouse Pointer Right](Screenshots/5%20Moving%20Mouse%20Pointer%20Right.png)

- **Left Click**
  ![Left Click](Screenshots/6%20Left%20Click.png)

- **Right Click**
  ![Right Click](Screenshots/7%20Right%20Click.png)

## Contributors
- **Prashanth G** (20QK1A0548)
- **Kodi Raju** (20QK1A0526)
- **P. Laxmi Sruthi** (20QK1A0545)
- **T. Pranitha** (20QK1A0562)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
