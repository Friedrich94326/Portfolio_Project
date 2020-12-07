# **Portfolio Project: Real-time Face Recognition, Age & Gender Estimation Using Keras**


## **Mind map for this project**

## Stage Management

***Phase*** | ***Description***
---- | ---
Build a face detector | by MTCNN
Create a complete dataset | 5_celebrities_dataset <br> my_family_and_friends <br/>
Build a face classifier | transfer learning <br> fine-tuning the pre-trained FaceNet model <br/>
Integrate system | Integrate detector and classifier into the entire recognition system
Display control | Use OpenCV VideoCapture() to receive video stream <br> Display bounding box, predicted label, and its probability on the screen <br/>
Compare other models | Use other common pre-trained neural networks (e.g., VGG-16, DeepFace, Haar cascade) to perform our task


## **Project Objectives:**
(1) Construct a real-time face detector which displays a bounding box of a detected face and its confidence based on MTCNN <br/> &nbsp; &nbsp; (Haar Cascade as an alternative) and OpenCV. [**DONE**] \
(2) Create a base model using pre-trained models (FaceNet, DeepFace, VGG-16). \
(3) Build a dataset of my own images. As required, each image must have dimensions (160, 160, 3). \
(4) Image preprocessing. (Noise reduction by Kalman filter.) \
(5) Stack classification layers on the top of the base network and then compile it. Train and evaluate the newly built model. \
(6) Data visualisation.





## **Development Tools:**
TensorFlow-GPU: version 2.3.0 \
Keras: version 2.4.3 \
OpenCV: version 4.2.0 \
Python: version 3.6.9 \
FaceNet \
MTCNN \
Kalman Filter \
GUI \
Logitech C170 Webcam



## **References:**
(1) [《FaceNet: A Unified Embedding for Face Recognition and Clustering》](https://arxiv.org/abs/1503.03832)  \
(2) [《DeepFace: Closing the gap to human-level performance in face verification》](https://www.cs.toronto.edu/~ranzato/publications/taigman_cvpr14.pdf) \
(3) &nbsp; David Sandberg's prominent project: *[Face Recognition using Tensorflow](https://github.com/davidsandberg/facenet)* \
(4) &nbsp; *[MTCNN](https://github.com/ipazc/mtcnn)* for face detection \
(5) [《Face Detection in Python Using a Webcam》](https://realpython.com/face-detection-in-python-using-a-webcam/) \
(6) &nbsp;[Transfer Learning and Fine-tuning](https://www.tensorflow.org/tutorials/images/transfer_learning?fbclid=IwAR1h325gQ5L5S-QCwrlZWhsPE5qm4XGUsrsLJdjppzs_RABCOhxARn8voKA) \
(7) [《Face Recognition: Real-Time Face Recognition System using Deep Learning Algorithm and Raspberry Pi 3B》](https://medium.com/@BhashkarKunal/face-recognition-real-time-webcam-face-recognition-system-using-deep-learning-algorithm-and-98cf8254def7) \
(8) &nbsp; Chapter 14- Face Recognition [*Digital Image Processing: An Algorithmic Approach with MATLAB*](https://www.amazon.com/Digital-Image-Processing-Algorithmic-Textbooks/dp/1420079506), Uvais Qidwai and C.H. Chen
