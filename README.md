# Speech Recognition in Healthcare Using Deep Learning

This project performs **multiclass audio classification** on speech recognition using deep learning techniques. It aids in early detection of conditions (asthma, pneumonia, and bronchitis) by analyzing patient-recorded respiratory sounds from coughs, speech, and breathing.

## Project Overview

- **Domain:** Deep Learning in Healthcare (Audio Processing)
- **Techniques:** MFCC Feature Extraction, CNN, Audio Augmentation
- **Categories Detected:** Asthma, COPD, Pneumonia, Bronchitis, Healthy
- **Best Test Accuracy:** 86.48%
  
## Workflow

1. Load audio dataset and extract MFCC features  
2. Apply data augmentation (noise, pitch shift, time stretch)  
3. Generate spectrograms  
4. Train CNN model  
5. Evaluate using Confusion Matrix, ROC Curve, and AUC  
6. Analyze results and test real-time inputs

## Tools & Libraries

- Python (Jupyter Notebook)
- TensorFlow
- Librosa
- Scikit-learn
- Matplotlib
- Seaborn
- Keras  

## Team Member

**Richik Dey**    
B.Tech – Information Technology  
Kalinga Institute of Industrial Technology (KIIT), Bhubaneswar, Odisha    
Project Type: Group  
Guide: Dr. Partha Sarathi Paul  

## License

This repository is for academic and demonstration purposes only. 
