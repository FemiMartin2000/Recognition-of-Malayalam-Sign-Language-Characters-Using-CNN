# Recognition-of-Malayalam-Sign-Language-Characters-Using-CNN
This project focuses on recognizing Malayalam Sign Language (MSL) characters using a Convolutional Neural Network (CNN). It is designed to assist in bridging the communication gap for people with hearing and speech impairments by accurately identifying hand gestures corresponding to MSL characters.

---


## Features
- **Image-based sign language recognition**: Captures hand gestures and translates them into text.
- **Deep learning with CNN**: Uses a VGG-16 based CNN model for classification.
- **Edge detection & preprocessing**: Implements Canny edge detection and morphological dilation for better feature extraction.
- **Real-time gesture recognition**: Uses a webcam for real-time input processing.

## Technologies Used
- **Python**
- **OpenCV** (for image processing)
- **TensorFlow/Keras** (for CNN implementation)
- **Matplotlib & NumPy** (for data visualization and processing)
- **DroidCam** (for real-time video feed)

## Installation
### **Prerequisites**
Ensure you have the following installed:
- Python 3.x
- TensorFlow/Keras
- OpenCV
- NumPy & Matplotlib

### **Steps**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/malayalam-sign-language-cnn.git
   cd malayalam-sign-language-cnn
   ```


## Dataset
The dataset consists of hand gesture images representing Malayalam Sign Language characters. Images undergo preprocessing (grayscale conversion, edge detection, morphological transformations) before being fed into the CNN model.

## Model Training
- **CNN Architecture**: Uses **VGG-16** for feature extraction.
- **Training & Validation**: Achieved **99% training accuracy** and **83% validation accuracy**.

## Results
The model successfully predicts Malayalam sign language characters in real-time with a high degree of accuracy. The output is displayed on the screen.

## Future Improvements
- Extend to **dynamic gestures** (not just static characters).
- Implement **real-time translation** into complete words/sentences.
- Develop a **mobile/web application** for broader accessibility.



## License
This project is licensed under the **MIT License**.

