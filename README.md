# Chapter 3: Computer Vision and Natural Language Processing

This repository contains team-based assignments in Computer Vision and Natural Language Processing (NLP). Each assignment focuses on real-world applications, including image enhancement, object detection, and text classification, using advanced techniques like transfer learning and pretrained models.

## Notebooks Overview

### 1. Image Enhancement Techniques (03_Tim_6_1.ipynb)
This notebook demonstrates methods to enhance photo quality in low-light conditions, simulating smartphone camera functionalities.

- **Goal:** Improve low-light image clarity using Max Pooling and CLAHE (Contrast Limited Adaptive Histogram Equalization).

#### Key Steps:
- **Basic Image Processing:** Convert images to grayscale and binary formats and visualize histograms.
- **Pooling Techniques:** Experiment with Max, Min, and Average Pooling methods.
- **Contrast Enhancement:** Apply CLAHE for better contrast in dark images.
- **Save Enhanced Images:** Save processed images with consistent labeling.

### 2. Transfer Learning for Handwritten Digit Classification (03_Tim_6_2.ipynb)
This notebook applies transfer learning on pretrained models to classify handwritten digits from the MNIST dataset.

- **Goal:** Fine-tune pretrained models (ResNet18, DenseNet121, Vision Transformer) for digit recognition.

#### Key Steps:
- **Model Customization:** Adjust input and output layers to fit MNIST data.
- **Hyperparameter Tuning:** Optimize settings like batch size, learning rate, and layer freezing.
- **Training and Evaluation:** Train models and assess their performance using accuracy and loss metrics.

### 3. Object Detection using YOLOv5 (03_Tim_6_3.ipynb)
This notebook uses a pretrained YOLOv5 model for real-time object detection on video streams.

- **Goal:** Perform object detection in real-time by adding bounding boxes and labels to identified objects.

#### Key Steps:
- **Video Retrieval:** Capture frames from YouTube video URLs.
- **YOLOv5 Detection:** Detect objects frame-by-frame using YOLOv5.
- **Performance Assessment:** Measure detection accuracy and frames per second (FPS) for real-time performance.

### 4. Disaster Tweet Classification with BERT (03_Tim_6_4.ipynb)
This notebook uses the BERT model to classify disaster-related tweets, supporting better disaster response through social media analysis.

- **Goal:** Fine-tune BERT for binary classification to identify disaster-related tweets.

#### Key Steps:
- **Data Preprocessing:** Clean tweets by removing URLs, HTML tags, and stopwords.
- **Tokenization:** Convert text to tokens suitable for BERT processing.
- **Model Training and Evaluation:** Train BERT, evaluate accuracy, and analyze classification results.

## Running the Notebooks

1. Open **Google Colab**.
2. Upload the required datasets and any necessary files as outlined in each notebook (`03_Tim_6_1.ipynb` to `03_Tim_6_4.ipynb`).
3. Follow each notebook's instructions to install additional dependencies if required.
4. Run cells in sequence for a smooth, structured analysis and model training experience.
