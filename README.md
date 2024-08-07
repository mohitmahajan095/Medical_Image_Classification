# Medical Image Classification Web App

This project utilizes a deep learning model trained with Google Teachable Machine to classify images into four categories: MRI, CT, X-Ray, and non-medical images. The trained model is integrated into a Streamlit web application to provide an interactive interface for users to upload and classify images.

> Wanna try the model ?
> https://medicalimageclassification.streamlit.app/
## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [License](#license)

## Introduction
Medical Image Classification Web App is a tool designed to make the process of classifying medical images straightforward and accessible. By leveraging Google Teachable Machine and Streamlit, the project combines an intuitive training process with an easy-to-use web interface. 

**Note:** Python version 3.9.0 is required to deploy on streamlit

## Features
- **Google Teachable Machine**: Train a deep learning model with a user-friendly interface.
- **Deep Learning Model**: Exported as a `.h5` file for easy integration.
- **Streamlit Web App**: Interactive platform for image upload and classification.
- **Image Categories**: Classify images into MRI, CT, X-Ray, and non-medical images.
- **User-Friendly**: Accessible for both medical professionals and laypersons.

## Installation
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/mohitmahajan095/Medical_Image_Classification.git
    cd Medical_Image_Classification
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download the Model**:
   Place the `.h5` file trained using Google Teachable Machine into the project directory.

## Usage
1. **Run the Web App**:
    ```bash
    streamlit run app.py
    ```

2. **Upload and Classify Images**:
   - Open the web app in your browser.
   - Use the upload button to select an image.
   - The app will display the classification result.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
