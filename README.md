# Human Activity Recognition (HAR) with Deep Learning  

This repository contains my work on **Human Activity Recognition (HAR)** using deep learning models, focusing on lightweight architectures optimized for **real-time inference** on edge and mobile devices.  


## Project Overview  
- Implemented **2D CNN architectures** for human activity recognition.  
- Trained and tested models on benchmark datasets:  
  - **UCI HAR** (smartphone-based motion data)  
  - **WISDM** (accelerometer-based activity dataset)  
  - **PAMAP2** (physical activity monitoring with wearable sensors)  
  - **Custom dataset** (collected and preprocessed for experiments)  
- Applied **quantization, pruning, and model compression** to balance accuracy and efficiency.  
- Explored deployment with **TensorFlow Lite** and **ONNX** for **edge AI applications**.  
- Created a `predict_log` pipeline to generate real-time predictions and maintain logs.  


## Repository Structure  
├── UCI_HAR_CNN.ipynb # CNN model training & evaluation on UCI-HAR dataset
├── WISDM_Arin_Work.ipynb # CNN model training & evaluation on WISDM dataset
├── Pamap2(5_models).ipynb # Multiple CNN models trained on PAMAP2 dataset
├── 2D_CNN_HAR(Arin).ipynb # Custom CNN architecture for HAR
├── predict_log.ipynb # Prediction pipeline with logging functionality
├── README.md # Project documentation

## Features  
- Custom **CNN-based HAR architecture**.  
- **Cross-dataset evaluation** to ensure generalization.  
- **Lightweight deployment** using pruning, quantization, and compression.  
- **Real-time prediction logs** for activity monitoring.  

