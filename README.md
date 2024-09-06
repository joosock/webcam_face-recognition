git clone https://github.com/joosock/webcam_face-recognition.git

git clone https://github.com/opencv/opencv.git

pip install opencv-python

cp opencv/data/haarcascades -R webcam-face-recognition/

cd webcam-face-recognition

python3 face_Recognition.py
