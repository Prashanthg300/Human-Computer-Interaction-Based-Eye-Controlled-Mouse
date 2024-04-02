# Human-Computer Interaction (HCI) Mouse Cursor Control

This Python 3.6 application offers an innovative method for controlling your computer's mouse cursor using facial movements detected through a standard webcam. By leveraging your facial expressions, such as squinting, winking, head movements, and slight mouth opening, this application provides a hands-free interaction experience without the need for any additional hardware or sensors.

## Features

- Control the mouse cursor through intuitive facial movements.
- Hands-free interaction, no wearable hardware required.
- Customizable facial movements (configurability in progress).

## Supported Actions

- **Squinting:** Partially closing the eyes, mimicking response to bright sunlight.
- **Winking:** Briefly closing one eye.
- **Head Movement:** Nodding (pitch) and turning (yaw) your head.
- **Mouth Opening:** Slight opening of the mouth.

## Acknowledgments

Special thanks to Adrian Rosebrock for his insightful blog posts, code snippets, and the imutils library, which played a crucial role in bringing this project to life.

## Code Requirements

Ensure you have the following dependencies installed:

- Numpy (version 1.13.3)
- OpenCV (version 3.2.0)
- PyAutoGUI (version 0.9.36)
- Dlib (version 19.4.0)
- Imutils (version 0.4.6)

## Execution

To run the application:

1. Install the required dependencies as per the installation guides provided by each library.
2. Download the model required for the application. Refer to the README.txt file within the model folder for the download link.
3. Execute the application by running the following command:

   ```bash
   python mouse-cursor-control.py
