# Image Caption Generator using Deep Learning

A deep learning-based image captioning system that automatically generates textual descriptions for images using CNN-LSTM architectures, transfer learning, and sequence modeling techniques.

This project combines Computer Vision and Natural Language Processing (NLP) to generate meaningful captions from input images.

---

## Overview

Image captioning is a multimodal AI task that combines:

- Image Feature Extraction (Computer Vision)
- Sequence Generation (Natural Language Processing)
- Deep Learning-based Caption Prediction

The model extracts visual features from images using pretrained CNN architectures such as VGG16 and ResNet50, and generates captions using LSTM-based sequence models.

---

## Features

- Automatic image caption generation
- Transfer learning using pretrained CNNs
- VGG16 and ResNet50 feature extraction
- LSTM-based sequence generation
- Flickr8k dataset support
- BLEU score evaluation
- Caption prediction on real-world images
- End-to-end deep learning pipeline

---

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- NLTK
- ResNet50
- VGG16

---

## Dataset

This project uses the Flickr8k Dataset for image captioning tasks.

Dataset Source:
https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip

The dataset contains:
- 8,000 labeled images
- Multiple captions per image
- Real-world scene descriptions

---

## Project Workflow

1. Load and preprocess image-caption dataset
2. Clean and tokenize captions
3. Extract image features using pretrained CNNs
4. Build vocabulary and sequence encodings
5. Train CNN-LSTM caption generation model
6. Generate captions for unseen images
7. Evaluate predictions using BLEU scores

---

## Model Architecture

The architecture combines:

### Image Encoder
- VGG16 / ResNet50 pretrained CNN
- Transfer learning for feature extraction

### Text Decoder
- Embedding Layer
- LSTM Network
- Dense Layers

### Caption Generator
- Combines image and text features
- Predicts next word sequentially

---

## Sample Prediction

![Sample Prediction](assets/sample_prediction.png)

Example generated caption from the trained image captioning model.

---

## Results

The model successfully generates contextual captions for images from the Flickr8k dataset.

Example outputs include:
- "A dog running through the grass"
- "A child playing with a ball"
- "Two people riding bicycles"

The project also evaluates caption quality using BLEU score metrics.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/GantiYasaswini/image-caption-generator.git
cd image-caption-generator
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Repository Structure

```text
image-caption-generator/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
├── image_captioning.ipynb
│
├── assets/
│   ├── sample_prediction.png
│   ├── generated_captions_1.png
|   ├── generated_captions_2.png
│   ├── model_architecture.png
|   ├── caption_4.png
│   └── caption_3.png
```

---

## Key Concepts Used

- Convolutional Neural Networks (CNNs)
- Transfer Learning
- Long Short-Term Memory (LSTM)
- Sequence Modeling
- Natural Language Processing
- Computer Vision
- Feature Extraction
- Deep Learning for Multimodal AI

---

## Future Improvements

- Attention-based image captioning
- Transformer-based caption generation
- Beam search decoding
- Larger datasets such as MS COCO
- Real-time caption generation
- Web application deployment

---

## Acknowledgements

- Flickr8k Dataset
- TensorFlow & Keras
- ResNet50 & VGG16 pretrained models
- NLTK NLP toolkit

---

## Author

Developed as part of deep learning and multimodal AI experimentation focused on image understanding and natural language generation.
