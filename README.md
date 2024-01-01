# Plant 🌱 Disease 🐛 Detection 🔎

Plant Disease Detection is a machine learning project that leverages Convolutional Neural Networks (CNN) and deep learning techniques to identify and classify diseases in plants. The goal is to provide a tool for farmers and agricultural experts to quickly diagnose plant health, enabling timely intervention and reducing the risk of crop loss.

[Live Demo](https://saurabhsinghdhami-plant-disease-detection-main-app-p8d5ks.streamlit.app/)

## Project Structure

The project consists of the following key components:

- `Plant_Disease_Detection.ipynb`: Jupyter Notebook containing the code for model training.
- `main_app.py`: Streamlit web application for plant disease prediction.
- `plant_disease_model.h5`: Pre-trained model weights.
- `requirements.txt`: List of required Python packages for the project.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/Plant-Disease-Detection.git
cd Plant-Disease-Detection
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Run the Streamlit web application:

```bash
streamlit run main_app.py
```

## Usage

Once the application is running, open your web browser and navigate to [http://localhost:8501](http://localhost:8501). Upload an image of a plant leaf, and the system will predict if it is affected by any disease.

## Model Training

The model was trained using the `Plant_Disease_Detection.ipynb` notebook. It utilizes a Convolutional Neural Network architecture to classify plant images into different disease categories. The trained model weights are saved in `plant_disease_model.h5`.

## Web Application

The web application (`main_app.py`) allows users to interact with the trained model. Users can upload images, and the application will provide real-time predictions regarding the health of the plant.

## Requirements

- Keras==2.8.0
- numpy==1.21.4
- streamlit==1.18.0
- opencv-python-headless==4.5.3
- tensorflow==2.7.0
