# Violence Detection in Surveillance from Drones

This project is designed to use a drone with a set of sensors to detect fights within a certain territory. To detect fights, the drone uses a camera and computer vision algorithms that work in two stages.

## Task Description

The drone must fly along the perimeter of the territory and detect people who may be involved in a fight. The drone must then approach the intended area of the fight to make sure that a fight is actually taking place. If a fight is detected, the drone must report it.

## Solution architecture

This project consists of two main parts: an algorithm for detecting people and an algorithm for detecting fights.

### Detecting people

To detect people, we use computer vision algorithms that determine the contours of people in images taken from the drone's camera. We also use neural networks to recognize movement patterns that may indicate that a group of people is involved in a fight.

### Fight detection

When the drone detects a group of people who may be involved in a fight, it approaches that area and uses computer vision algorithms to determine if a fight is taking place there. To do this, we use algorithms that determine movement patterns and brutality.

## Software Requirements

- Python 3.x
- Libraries for computer vision: OpenCV, NumPy, SciPy
- Libraries for training neural networks: TensorFlow, Keras

## Installation and use

1. Clone this repository to your computer
2. Install all necessary libraries using pip
3. Launch the drone and the software on the computer connected to the drone
4. Run the script `detect_fights.py `to start searching for fights

## Contribution to the project
We welcome any contribution to this project. If you have any ideas or suggestions to improve the detection of fights, please create a branch and send a request for influence. We also welcome bug fixes and code improvements.

## License

This project is distributed under the MIT license. We make sure that all libraries and frameworks used in the project are also distributed under their respective licenses.

## Assistance

We thank you for using our software. If you have any questions or problems with using the drone and the software, please create a new task in the Issues section of our repository on GitHub.

With respect,

[Name of the Project manager]
