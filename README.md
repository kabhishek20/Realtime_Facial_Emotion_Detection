# Realtime_Facial_Emotion_Detection
 
A **Deep Learning Project** in which I built a **Convolutional Neural Network** to detect **7 different facial emotion in live camera**.

- A CSV file containing **28709 training images** was used to train the model.

- The model was tested on **3589 images** and had an accuracy of **83.95%**.

- The model was trained for **100 epochs** with a **batch size of 64**.
I had NVIDIA GPU in my laptop, so it took roughly **33 seconds for 1 epoch**.

- **Conv2D layer** was added with a **kernel size of 3*3**  and had **relu activation**.

- The model was **flattened** after the addition of **Conv2d layers** and a **Dense neural network** was formed.

- The final dense layer has **softmax as its activation function**.

- Finally the model was compiled with **Adam** as the optimizer.