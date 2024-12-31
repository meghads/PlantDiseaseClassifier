# Plant Disease Classifier using DL

This project leverages deep learning techniques, specifically Convolutional Neural Networks (CNNs), to detect plant diseases from images. The web interface for the application is implemented using Streamlit, making it interactive and user-friendly.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Technologies Used](#technologies-used)
5. [How to Run](#how-to-run)
6. [Usage](#usage)

---

## Introduction

This project aims to assist farmers and agriculturists by identifying plant diseases early through image recognition. By using CNN models, the system classifies images of plant leaves into categories based on the disease present or identifies them as healthy.

---

## Features

- Upload an image of a plant leaf to detect its health status.
- Provides the name of the disease (if any) affecting the plant.
- Offers a simple and intuitive user interface built using Streamlit.

---

## Dataset

The dataset used in this project consists of images of healthy and diseased plant leaves. Each image is labeled with the corresponding plant species and disease. The dataset was preprocessed to normalize image sizes and enhance the quality of input data.

---

## Technologies Used

- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow/Keras
- **Web Framework**: Streamlit
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib

---

## How to Run

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/siddhardhan23/PlantDiseaseClassifier.git
   ```

2. Navigate to the project directory:

   ```bash
   cd PlantDiseaseClassifier
   ```

3. Install the required Python libraries:

   ```bash
   pip install numpy tensorflow streamlit
   ```

4. Run the Streamlit application:

   ```bash
   cd app
   streamlit run main.py
   ```

5. Open the URL provided by Streamlit in your browser to interact with the application.

---

## Usage

1. Launch the application by following the steps in the "How to Run" section.
2. Upload an image of a plant leaf through the interface.
3. Wait for the model to process the image.
4. View the prediction results and disease information displayed on the screen.

---


### Note

Docker was not used in this implementation. Instead, the application is directly run using Streamlit. Ensure all dependencies are installed before running the application.

