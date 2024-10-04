# -Emotion-Analysis-from-Albanian-Speech-Data
This study aims to perform emotion classification using mel-spectrograms from Albanian audio data.

# Deep Learning-Based Emotion Analysis and Classification from Albanian Speech Data

## Authors
- Prof. Dr. Bahadır KARASULU - bahadirkarasulu@comu.edu.tr 
- Elif AVCI - elffavci@gmail.com
- Tesnim STRAZIMIRI - tesnimastrazimiri@gmail.com
- Betül CENGİZ - cengizzbetul@gmail.com


## Overview
This project aims to classify emotions by obtaining mel spectrograms from Albanian speech data. Emotion recognition plays a crucial role in human-computer interaction. Mel spectrograms, which are time-frequency representations of audio signals, provide a rich feature set for emotion classification models. 
Automatically classifying emotional states from speech data is of great importance, particularly in the fields of natural language processing and human-computer interaction. In this study, a system was developed to classify four basic emotions (happy, sad, angry, surprised). The goal is to accurately detect these emotions using mel spectrograms and deep learning models.

## Dataset Used
The dataset used in our study consists of audio recordings from 9 Albanian individuals. Each individual recorded 4 sentences to represent 4 different emotional states (happy, sad, angry, surprised). These audio recordings were first converted into mel spectrograms, and the training set was expanded using data augmentation techniques. Mel spectrograms, as time-frequency representations of audio signals, provide a rich feature set for model training.

## Key Features and Methodology
- **Emotion Detection:** Detection and classification of emotional states from Albanian speech data using deep learning models.
- **Spectral Analysis:** Conversion of audio data into mel spectrograms for detailed time-frequency domain analysis.
- **Models Used:** Convolutional Neural Network (CNN) models used for training and classification tasks. (In our project, ResNET50 and Xception were utilized.)
- **Dataset Creation:** Audio data was collected from 9 different speakers, with recordings representing four emotions: angry, happy, sad, and surprised.
- **Data Preprocessing:** Audio data was converted into mel spectrograms using the Librosa library.
- **Model Training:** Mel spectrograms were trained on CNN models to classify emotions in speech data using transfer learning.
- **Model Performance and Evaluation:** The model was evaluated based on performance metrics such as accuracy and loss values, precision, recall, F1 Score, confusion matrix, ROC, and AUC curve.

## Conclusion
In this study, deep learning models were successfully developed and evaluated to identify emotions from audio data using mel spectrograms. The goal was to classify emotional states using advanced image classification models such as Xception and ResNet-50. The results indicate that these models can effectively classify emotional states using mel spectrograms.

During the training process, both models showed a rapid increase in accuracy. Training accuracy reached 100%, and training loss was reduced to almost zero. Validation accuracy gradually increased, reaching 75% for the Xception model and 85% for the ResNet-50 model. Validation loss remained stable at a certain level. These results demonstrate that both models perform well in identifying emotions using mel spectrograms.

Recommended topics for future research include using larger and more diverse datasets, optimizing model hyperparameters, and exploring different deep learning architectures. These steps are crucial for further improving model performance and enhancing generalization capabilities.

## Setup

### Prerequisites
- Python 3.7 or higher
- Librosa for audio processing
- Matplotlib for visualization
- TensorFlow for deep learning model implementation
- Google Colab for execution
