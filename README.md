# Speech Recognition in Healthcare Using Deep Learning

This project performs **multiclass audio classification** on patient-recorded respiratory sounds using deep learning. It aids in early detection of conditions like asthma, pneumonia, and bronchitis by extracting MFCC features from coughs, speech, and breathing.

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

amazon-sentiment-analysis/
│
├── README.md                  ← Overview of your project 
├── requirements.txt           ← All Python dependencies 
├── sentiment_analysis.ipynb   ← Your Colab notebook (cleaned) 
├── balanced.csv               ← Dataset (if allowed to share) 
├── output/                    ← Screenshots or sample results (optional) 
├── report/                    ← Final project report PDF/DOCX (optional) 

