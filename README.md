# Final Project for Large Language Models

## Project Overview

This project focuses on generating radiology reports from chest X-rays using Transformer architectures. The aim is to leverage advanced deep learning techniques to automate the reporting process, which can improve efficiency and accuracy in clinical settings.

### Project Highlights

- **Project Title**: Generating Radiology Reports from Chest X-rays
- **Datasets**:
  - [MIMIC-CXR](https://physionet.org/content/mimic-cxr/2.0.0/)
  - [IUC-CXR](https://openi.nlm.nih.gov/imgs/collections/NLM-MontgomeryCXRSet.zip)
- **Encoder Architectures**:
  - Convolutional Vision Transformer (CvT)
  - Vision Transformer (ViT)
- **Decoder Architecture**:
  - DistillGPT2

### Acknowledgements

Special thanks to the developers of [cvt2distilgpt2](https://github.com/aehrc/cvt2distilgpt2) for making their code publicly available, which served as a foundation for this project.

## Project Details

### Goals

The goal of this project is to create a model that can accurately generate diagnostic radiology reports from chest X-ray images. The use of advanced Transformer architectures allows for sophisticated processing of visual and textual data.

### Methodology

The project employs two Transformer-based encoder architectures, CvT and ViT, combined with a DistillGPT2 decoder. The model is trained and evaluated on two popular datasets, MIMIC-CXR and IUC-CXR, using various evaluation metrics.

### Results

The project assesses the generated reports using linguistic metrics such as ROUGE and BLEU, as well as the Clinical Efficacy (CE) metric, to ensure clinical relevance and accuracy.


