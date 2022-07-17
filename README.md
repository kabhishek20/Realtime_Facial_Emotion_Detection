# Realtime_Facial_Emotion_Detection
 
A <code>**Deep Learning Project**</code> in which I built a <code>**Convolutional Neural Network**</code> to detect <code>**7 different facial emotion in live camera**</code>.

- A CSV file containing <code>**28709 training images**</code> was used to train the model.

- The model was tested on <code>**3589 images**</code> and had an accuracy of <code>**83.95%**</code>.

- The model was trained for <code>**100 epochs**</code> with a <code>**batch size of 64**</code>.
I had NVIDIA GPU in my laptop, so it took roughly <code>**33 seconds for 1 epoch**</code>.

- <code>**Conv2D layer**</code> was added with a <code>**kernel size of 3*3**</code>  and had <code>**relu activation**</code>.

- The model was <code>**flattened**</code> after the addition of <code>**Conv2d layers**</code> and a <code>**Dense neural network**</code> was formed.

- The final dense layer has <code>**softmax as its activation function**</code>.

- Finally the model was compiled with <code>**Adam**</code> as the optimizer.

- The model was saved in the form of json and was reused in the videotester.py file which is used to detect face from the live camera.

> iypnb file : [Click here](https://github.com/kabhishek20/Realtime_Facial_Emotion_Detection/blob/main/Realtime_Emotion_Detection.ipynb)

> json model : [Click here](https://github.com/kabhishek20/Realtime_Facial_Emotion_Detection/blob/main/Emotion_Model.json)

> haarcascade : [Click here](https://github.com/kabhishek20/Realtime_Facial_Emotion_Detection/blob/main/haarcascade_frontalface_default.xml)

> Videotester : [Click here](https://github.com/kabhishek20/Realtime_Facial_Emotion_Detection/blob/main/videoTester.py)