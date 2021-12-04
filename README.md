# Face-Detection-Recognition
𝗙𝗮𝗰𝗲 𝗗𝗲𝘁𝗲𝗰𝘁𝗶𝗼𝗻 𝗮𝗻𝗱 𝗥𝗲𝗰𝗼𝗴𝗻𝗶𝘁𝗶𝗼𝗻 𝗺𝗼𝗱𝗲𝗹 𝘂𝘀𝗶𝗻𝗴 𝗣𝘆𝘁𝗵𝗼𝗻, 𝗠𝗮𝗰𝗵𝗶𝗻𝗲 𝗟𝗲𝗮𝗿𝗻𝗶𝗻𝗴 𝗮𝗻𝗱 𝗖𝗼𝗺𝗽𝘂𝘁𝗲𝗿 𝗩𝗶𝘀𝗶𝗼𝗻 𝗹𝗶𝗯𝗿𝗮𝗿𝘆 𝗰𝗮𝗹𝗹𝗲𝗱 𝗢𝗽𝗲𝗻𝗖𝗩.




##  ▶️ OPENCV

OpenCV is a Library which is used to carry out image processing using programming languages like python. This project utilizes OpenCV Library to make a Real-Time Face Detection using your webcam as a primary camera.

## ▶️ COMPUTER VISION 

Computer vision involves seeing or sensing a visual stimulus, make sense of what it has seen and also extract complex information that could be used for other machine learning activities.

### FUNCTIONS 

#### CREATE DATASET :

⏩ I will try to detect the face of individuals using the ``` haarcascade_frontalface_default.xml ```
The dimensions of the image that we have used here was pretty large, so I have scaled down the image dimensions for better output.

#### TRAIN THE MODEL : 

⏩ This project uses LBPH (Local Binary Patterns Histograms) Algorithm to detect faces. It labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.

#### RECOGNITION 

⏩ After training the model , I make the recognition of faces 


### HOW TO RUN THIS PROJECT 

#### Pre-Requisities:

- install python3 
- install openCV 
- install numpy 
- install face 
- install pillow 

#### OPEN TERMINAL : 

 Open Terminal and Execute Following Commands :

``` 
install python3
apt install python3-pip
pip install opencv-python3
pip install numpy
pip install face 
pip install pillow
pip install opencv-contrib-python
```

#### RUN PROJECT 

##### 1️⃣ FIRST STEP 

 👉 create Dataset 

 ``` python3 Face_dataset.py ```

 ##### 2️⃣ SECOND STEP 

👉 train the model 

``` python3 training.py ```

 ##### 3️⃣ FINAL STEP

 ``` python3 Face_recognition.py ```
 
  












