# Face_recognition_Custom_model

This is a quick guide of how to get set up and running a robust real-time facial recognition system using the Pretraiend Facenet Model and MTCNN.

1. Make a directory of your name inside the Faces folder and upload your 2-3 pictures of you.
2. Download the pre-trained model and add into the "model" folder.
3. Run ` train_v2.py`.
4. Then run `detect.py` for realtime face recognization.

As the Facenet model was trained on older versions of TensorFlow, the architecture.py file is used to define the model's architecture on newer versions of TensorFlow so that the pre-trained model's weight can be loaded.<br>

Dowload pre-trained weight from [Here.👈](https://drive.google.com/drive/folders/1R4musrWeMDWkZ6OFqyLg6ml9eaFJuhKI?usp=share_link) <br>
Reference and idea by  [article. 👈](https://arsfutura.com/magazine/face-recognition-with-facenet-and-mtcnn/)

# Dependencies

This code was working properly on tensroflow 2.3.0.

```
Tensorflow 2.X
numpy
opencv-python
mtcnn
scikit-learn
scipy
```
