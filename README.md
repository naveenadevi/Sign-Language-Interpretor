#  Sign Language Interpreter using CNN

A real-time sign language recognition system that uses Convolutional Neural Networks (CNNs) to classify hand gestures captured via webcam.

Designed to bridge the communication gap for individuals with hearing or speech impairments by translating hand signs into readable text.

---

##  Key Features

-  Real-time hand gesture recognition using webcam input
-  Trained CNN model on labeled image dataset of hand signs
-  Translates static signs into corresponding alphabet/words
- 🖥 User-friendly interface for live classification

---

##  Tech Stack

- Python  
- OpenCV  
- Keras + TensorFlow  
- NumPy, Matplotlib  
- Jupyter Notebook  

---

##  Dataset

- Custom or Kaggle dataset of hand sign images
- Augmented with flipping, rotation, scaling for better generalization

---

## Model Performance

- CNN achieved high accuracy (90%+) on validation set
- Live inference runs smoothly on standard webcam

---

##  Project Structure

dataset/ # Image data for training
model/ # Trained CNN model
realtime.py # Webcam-based live classification
train_model.py # CNN model training script

##  How to Run

# Train the model (if not pre-trained)
python train_model.py

# Run real-time sign recognition
python realtime.py

---
##   Future Enhancements
Integrate with voice output for speech synthesis

Extend support to dynamic gestures (sentence-level recognition)

Deploy as a mobile or web app
