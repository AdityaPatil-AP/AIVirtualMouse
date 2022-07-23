# AIVirtualMouse Using OpenCV


For the Capstone Project of second semester, our team has developed AI Virtual Mouse using OpenCV which is based on finger detection and can perform various mouse callback functions. It follows the trail of your index finger☝️ to move the cursor of your mouse🖱️ and can perform other functions with gestures like,

2 finger up for left click✌️,

3 finger up for right click,

Index finger and pinky finger for scrolling down,🤘

Thumb and pinky finger for scrolling up.🤙

![image](https://user-images.githubusercontent.com/94468283/180596270-5bbd6a44-8dcf-4a43-b891-319ee0ea9166.png)

There are two python files : 
1) AiVirtualMouseProject.py - It acts as the main source code file which handles all the functions which we have implemented. 
2) HandDetectorModule.py : It helps in processing of images in order to detect our hands and then according to input it provides the specific functionality and redirects to the source code.

![image](https://user-images.githubusercontent.com/94468283/180596383-1200143f-d709-4f6e-87bb-551eb6cbde7b.png)

Modules used for the program are OpenCV for Video Capture and processing, HandTrackingModule for detection and processing of fingers seen through camera which is done using Mediapipe by Google, Numpy for arrays, autopy and pyautogui for all mouse functions. Jupyter Notebook for testing and running the program.

One of the main advantages of this program is that we can choose any set of gestures we want for any particular mouse function. We can add more mouse or even keyboard⌨️ functions with other set of fingers to make the program effective and stack more functions in a single program.

This system can be used by specially abled people🧑‍🦽 to access their PCs or even help the professors and teachers🧑‍🏫 in effective teaching via projector📽️ without the need of staying with the mouse all time.

It can be used on any desktop🖥️ or laptop💻 having webcam and there's no specific set of PC hardware requirements while you might need proper lighting conditions for efficient detection of your fingers.
