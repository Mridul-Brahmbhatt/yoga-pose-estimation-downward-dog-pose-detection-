# yoga-pose-estimation-downward-dog-pose-detection

this is an AI based project made to identify downward dog pose using the mediapipe library 

We are taking 6 features which are angles of left elbow,	right elbow, left shoulder,	left knee and	left hip

the angles which are taken are from the landmarks of mediapipe pose detection for full body

the fuction 'calculateAngle' is used here to find the angles taking three arguments to use each points x and y components. These points are then used in a trigonometric function to find the angle

## working

The deep learning model uses 3 layers and predict on the basis of angles given whether this pose is downward dog(0) or not(1). This dl model uses binary_crossentropy to find the outcome

If the outcome is 1 then it is a bad posture and if 0 then it is a good posture
