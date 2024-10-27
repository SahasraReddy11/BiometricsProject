UNMAKSKING VOICES: Speaker Identification and Diarization System
This project implements a speaker identification and diarization system leveraging machine learning techniques to accurately differentiate and classify speakers in audio recordings. By utilizing x-vector embeddings, spectral clustering, Support Vector Classifier (SVC), and Random Forest Classifier (RFC), the system aims to enhance the accuracy and efficiency of speaker identification and diarization tasks, with applications in speech recognition, surveillance, and forensic analysis.

Project Overview
The main goals of this project are:

To extract and identify unique speakers from audio recordings.
To classify speakers using advanced feature extraction and machine learning methods.
To evaluate the system's performance using diverse metrics like DER, accuracy, F1 score, and precision.
Key Features
Data Source: Utilizes a diverse dataset, including class voice recordings and a mini version of VoxCeleb.
Feature Extraction: Employs x-vector embeddings for extracting discriminative speaker features.
Speaker Clustering: Applies spectral clustering to group speakers effectively.
Speaker Classification: Uses SVC and RFC models to classify speakers based on extracted features.
System Architecture
The system architecture includes:

Data Preprocessing: Audio files are processed to extract relevant features.
Feature Extraction: x-vector embeddings are generated to capture distinct speaker characteristics.
Clustering and Classification: Spectral clustering, SVC, and RFC models are applied for accurate speaker separation and classification.
Evaluation: System performance is evaluated using metrics like DER, accuracy, F1 score, and precision.
