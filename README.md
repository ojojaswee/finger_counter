# Finger Counter using OpenCV and MediaPipe

![alt text](MediaPipe.png)
The diagram above shows a hand landmark model that shows how MediaPipe tracks hands. This program focuses on the hand knuckles.

The diagram shows numbers from 0 to 20 displayed over the knuckles. This program uses the position of these knuckles to determine whether a finger is open or closed.

Logic used to count the fingers in this program:

-> If knuckle number 8 is above knuckle number 6, then the finger is open. If it is below knuckle number 6, then the finger is closed.<br />
-> This will apply to all fingers except the thumb. For the thumb, we check whether knuckle number 4 is above knuckle number 2. If this is the case, then the thumb is open else, the thumb is closed.
