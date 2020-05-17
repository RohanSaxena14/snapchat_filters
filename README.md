# snapchat_filters 👽

Implementing fun snapchat_filters with the help of dlib facial_keypoint model.

Despite of being an easy project it is very much fun.

Firstly we have to be familier with facial_keypoints, that we will be using here,  (i am using a short mr bean's video clip for 
demostration here, Why?, well i guess because its fun)

## Facial_keypoints
Facial Keypoints are also called Facial Landmarks which generally specify the areas of the nose, eyes, mouth, etc on the face, classified by 68 key points, with coordinates (x, y), for that face. This is how it looks.

![](https://github.com/RohanSaxena14/snapchat_filters/raw/master/data/facial_keypoints_bean.png)

You can read about facial_keypoints here: 
https://towardsdatascience.com/facial-keypoint-detection-detect-relevant-features-of-face-in-a-go-using-cnn-your-own-dataset-e09cf359c2bc

## Clipart
Although you can take any clipart you like, just make sure it has a transparent background 😉 

we have used that to create a mask in the code, just to ensure the shape of the clipart is not changed.

we will be using this eye clipart. 👀

![](https://github.com/RohanSaxena14/snapchat_filters/raw/master/data/Eye.png)

## Key_points

All the keypoints are numbered like this, we are concerned with the points around the eyes 👀 for now.

![](https://github.com/RohanSaxena14/snapchat_filters/raw/master/data/facial_landmarks_68markup.jpg)

## Output
The output of this code looks like this: 😄✌

![](https://github.com/RohanSaxena14/snapchat_filters/raw/master/data/bean_output.gif)

connect with me on Linkdin:
https://www.linkedin.com/in/rohan-saxena-2846a5163/

HAPPY LEARNING !!! 😃
