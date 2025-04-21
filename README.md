# TheraReach
Developed a fully embedded robotic arm with 5 degrees of freedom, controlled by AI, to play games with you such as TicTacToe, along with an app to easily communicate with the robot and for game selection.

Hardware Used:
- 5x MG9964 12kg servos
- 1x 25kg servo
- PCA9865 Servo Driver
- Raspberry Pi 5 16gb
- 3D printed arm parts
- Buildable servo controlled arm grabber
- Power supply module with 2x AC/DC 5V 2A adapter power supply

Software Used:
- Raspberry Pi OS running python connected to the Arm
- External Server running python between the pi and a laptop, which hosts the website/app

AI Used:
- Convolutional Neural Network to train model to see different colored blocks with 90% accuracy
- OpenCV for camera/location detection providing serial communication to the servos

![IMG_1076](https://github.com/user-attachments/assets/a78a7170-989b-4d7b-958d-eb17928b1f9d)

![IMG_1077](https://github.com/user-attachments/assets/e33386e9-5f29-4194-ae8d-08fcaacd0864)

