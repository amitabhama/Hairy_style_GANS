# Hairy_style_GANS

## CPSC540 - each Sunday; before 5pm (finish it); let’s meet at 1pm
Idea - To generate desired hair style using dataset from face detection and already existing architecture of facial recognition and hair style recognition.

Idea - If the above works use something similar for generating image with desired glasses.

https://github.com/YBIGTA/pytorch-hair-segmentation - pretrained hair segmentation pytorch

https://github.com/tbmoon/facenet?fbclid=IwAR0wlh7bKUdAOxcgo4hlXUQCaBALvTA-vi3PKlxPqIOy7ECMDouuJXoBRu4 - face net

https://stackoverflow.com/questions/14167886/how-to-detect-front-and-side-view-of-human-face-using-opencv

OpenCv:

* http://alereimondo.no-ip.org/OpenCV/34
* https://github.com/informramiz/Face-Detection-OpenCV 


DataSet:

* VGG-Face2:
  * Username: vibudh
  * Password: vibudh2209
* UMDFaces Dataset: https://www.umdfaces.io/ 

What we have:

* We have hair segmentation network
* We have facial detection network
* We have facial image (VGG-face2), UMDFaces Dataset (https://www.umdfaces.io/ ) and hair image dataset (FIGARO)

Version one (portrait face):

* Pre process image to get only people with front view (USE DLIB FOR THIS!!! - http://dlib.net/face_detector.py.html?fbclid=IwAR3rA0MOrQ3Vr6QfQkmr7yqePm0Po8NQCOk4zhQwH7vSXhvG1b4hlnvyuZE) 
* Test out pre trained models on the dataset we have
* Make pairs for training
* Start building GAN!!!!Yay!!!

