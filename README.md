# Face-Emotion-Recognition-with-VGG16

# **Real-Time Facial Emotion Recognition**  

This project is a **real-time facial emotion recognition system** using deep learning. It is trained on the **FER2013 dataset** and fine-tuned with **AffectNet** to improve performance on underrepresented emotions. The model is integrated with **OpenCV** for real-time detection through a webcam.  

## **Features**  
- Detects **seven emotions**: Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise  
- Trained using **VGG** with transfer learning and fine-tuning  
- Real-time inference using **OpenCV**  

## **Dataset & Training**  
- **Primary Training**: FER2013 dataset  
- **Fine-Tuning**: AffectNet (focused on improving "Disgust" emotion detection)  
- Used **TensorFlow/Keras** for model training  
- Model checkpointing was used to restore the best-performing weights  

## **Installation**  
### **Requirements**  
- Python 3.x  
- TensorFlow/Keras  
- OpenCV  
- NumPy, Matplotlib  

### **Setup**  
1. Clone the repository  
   ```bash
   git clone https://github.com/elchinmammadov0/Face-Emotion-Recognition-with-VGG16.git
   cd your-repo
   ```  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run real-time detection  
   ```bash
   python real_time_detection.py
   ```  

## **Usage**  
- The system captures video from your webcam and detects emotions in real-time.  
- Detected emotions are displayed on the screen with bounding boxes.  

## **Results**  
- Achieved **65% accuracy** on FER2013 test set  
- Successfully detects emotions in real-time  

## **Future Improvements**  
- Enhance accuracy with more diverse datasets  
- Optimize model for better real-time performance  
- Deploy as a web or mobile application  

## **License**  
This project is licensed under the MIT License.  

