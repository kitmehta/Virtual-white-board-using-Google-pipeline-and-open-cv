# Virtual-white-board-using-Google-pipeline-and-open-cv
Fully automated whiteboard animation Using Python, Computer Vision and Google MediaPipe Libraries
python

PyTorch OpenCV MediaPipe license

Install Required Packages and Libraries
pip upgrade --user pip
pip install opencv-python
pip install numpy
pip install mediapipe

Virtual drawing board ✍️
The Virtual WhiteBoard is a project I made using the OpenCV and Mediapipe Python libraries. Ever wanted to draw your imagination by just waiving your finger in air. In this project I have  build an Air Canvas which can draw anything on it by just capturing the motion of a coloured marker with camera. Here a coloured object at tip of finger is used as the marker.

We will be using the computer vision techniques of OpenCV to build this project. The preffered language is python due to its exhaustive libraries and easy to use syntax but understanding the basics it can be implemented in any OpenCV supported language.

Here Colour Detection and tracking is used in order to achieve the objective. The colour marker in detected and a mask is produced. It includes the further steps of morphological operations on the mask produced which are Erosion and Dilation. Erosion reduces the impurities present in the mask and dilation further restores the eroded main mask.


Run Project
Open project from PyCharm or suitable IDE and run the VirtualPainter.py file or Open Command Prompt and Run python VirtualPainter.py
<img width="940" alt="HelloWorld" src="https://user-images.githubusercontent.com/52587652/159913976-d8e60a14-d445-46b2-89ce-cb032122a764.png">
![sample_project_img1](https://user-images.githubusercontent.com/52587652/159914247-947fd943-81a1-4a3d-8ef5-09ea006943f9.png)


