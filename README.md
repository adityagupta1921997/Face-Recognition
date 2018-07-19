# Face Recognition with OpenCV and Python

## Introduction

Face recognition is an easy task for humans. Experiments in [Tu06] have shown, that even one to three day old babies are able to
distinguish between known faces.
So how hard could it be for a computer?
It turns out we know little about human recognition to date.
Are inner features (eyes, nose, mouth) or outer features (head shape, hairline) used for a successful face recognition?
How do we analyze an image and how does the brain encode it?

Now the next question is how to code face recognition with OpenCV, after all this is the only reason why you are reading this article, right?
OK then. You might say that our mind can do these things easily but to actually code them into a computer is difficult?
Don't worry, it is not. Thanks to OpenCV, coding face recognition is as easier as it feels.
The coding steps for face recognition are:

- **Training Data Gathering:** Gather face data (face images in this case) of the persons you want to recognize
- **Training of Recognizer:** Feed that face data (and respective names of each face) to the face recognizer so that it can learn.
- **Recognition:** Feed new faces of the persons and see if the face recognizer you just trained recognizes them.

OpenCV comes equipped with built in face recognizer, all you have to do is feed it the face data. It's that simple and this how it
will look once we are done coding it.

Output:

![facerecognition](https://user-images.githubusercontent.com/30611434/42948078-5f5c68b6-8b8c-11e8-82ad-69809fbdbe70.png)

OpenCV has three built in face recognizers and thanks to OpenCV's clean coding, you can use any of them by just changing a single line of code.
Below are the names of those face recognizers and their OpenCV calls. 

1. EigenFaces Face Recognizer Recognizer - `cv2.face.createEigenFaceRecognizer()`
2. FisherFaces Face Recognizer Recognizer - `cv2.face.createFisherFaceRecognizer()`
3. Local Binary Patterns Histograms (LBPH) Face Recognizer - `cv2.face.createLBPHFaceRecognizer()`

Face Recognition is a fascinating idea to work on and OpenCV has made it extremely simple and easy for us to code it.
It just takes a few lines of code to have a fully working face recognition application and we can switch between all three face recognizers
with a single line of code change. It's that simple.

### Thanku...
