# 🌱 Smart Nutrient Deficiency Detector

A Machine Learning-based application that detects plant nutrient deficiencies from leaf images. The system uses a Convolutional Neural Network (CNN) to analyze leaf images and predict the possible nutrient deficiency.

## 📌 About the Project

Plant nutrient deficiencies can negatively affect plant growth and crop productivity. Identifying these deficiencies at an early stage can help in taking appropriate corrective measures.

This project uses image classification and deep learning techniques to identify nutrient deficiencies from plant leaf images.

## ✨ Features

- Upload a plant leaf image
- Analyze the uploaded image using a trained CNN model
- Predict the nutrient deficiency
- Display the predicted result through a simple application interface
- Supports image-based plant deficiency detection

- ## 🔄 How the System Works

1. The user uploads a plant leaf image.
2. The image is preprocessed before prediction.
3. The preprocessed image is passed to the trained CNN model.
4. The CNN model analyzes the leaf image.
5. The system predicts the possible nutrient deficiency.
6. The predicted result is displayed to the user.

## 🚀 How to Run the Project

1. Clone the repository.
2. Open the project folder.
3. Install the required dependencies using `requirements.txt`.
4. Run the Streamlit application using `streamlit run app.py`.
5. Upload a plant leaf image.
6. View the predicted nutrient deficiency.
- 

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- Convolutional Neural Network (CNN)
- NumPy
- OpenCV
- Streamlit
- Jupyter Notebook

## 🧠 Machine Learning Model

The project uses a Convolutional Neural Network (CNN) for image classification.

The model is trained to identify nutrient deficiencies such as:

- Nitrogen
- Phosphorus
- Potassium

## 📂 Project Structure

```text
plant_nutrient_deficiency_detector/
│
├── app.py
├── class_labels.json
├── demo.ipynb
├── requirements.txt
├── new_test_images/
├── .gitignore
└── .gitattributes
