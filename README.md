# virtual-volume-controller
I'll be learning how to change a computer's volume using Gesture Control in this project. I first research hand tracking, and then I use hand landmarks to identify a hand gesture that changes the volume. As this project is module-based, I will be using a hand module , which makes the hand tracking really simple.
A computer vision project.
Initially, I developed a handtracking module that uses mediapipe and the opencv library to track the landmarks on my hands.
Afterward, I import this module in gesture controlled volume to make it easy to track hand for volume control, then used pycaw library, which is Python Core Audio Windows Library, working for both Python2 and Python3.
![handtracking](https://user-images.githubusercontent.com/88935432/224565768-727c59b9-3e68-4d43-b657-eeffd1263d13.png)


References###
https://www.section.io/engineering-education/creating-a-hand-gesture-volume-controller-using-python-and-pycharm/
https://ijisrt.com/assets/upload/files/IJISRT22MAY250_(1).pdf
https://ijcrt.org/papers/IJCRT22A6059.pdf
https://www.computervision.zone/courses/hand-tracking/
