## Installation

To run this code, you need to install the following dependencies:

- Python 3.6+
- OpenCV (`pip install opencv-python`)
- Keras (`pip install keras`)
- NumPy (`pip install numpy`)
- Pygame (`pip install pygame`)

You will also need to download the Haar Cascade files for face, left eye, and right eye detection, which can be found here: https://github.com/opencv/opencv/tree/master/data/haarcascades.

Once you have installed the dependencies and downloaded the Haar Cascade files, you can run the code by running the following command in your terminal or command prompt:


Note that this code is designed to work with a webcam, so make sure you have a webcam connected to your computer before running the code.


## Usage
- Run the code using the command above.

- The camera window will open up and start detecting your face.

- Once your face is detected, the program will start monitoring your eye blinking patterns.

- If your eyes are closed for a certain amount of time, an alarm will sound to alert you.

- The score will increase as you keep your eyes open and decrease when you blink or close your eyes.

- If the score goes above a certain threshold, the alarm will sound.
