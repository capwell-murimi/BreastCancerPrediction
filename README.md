# Breast Cancer Prediction

This project is a web application that predicts the likelihood of breast cancer based on cytology data using a machine learning model. The app is built with Streamlit and uses a logistic regression model trained on the Wisconsin Breast Cancer dataset.

## Features

- Interactive sidebar for inputting cell nuclei measurements
- Radar chart visualization of input features
- Real-time prediction of benign or malignant diagnosis
- Probability scores for each prediction
- Custom styling for clear and accessible results

## Project Structure

```
.
├── README.md
├── requirements.txt
├── App/
│   └── main.py
├── assets/
│   └── style.css
├── data/
│   └── data.csv
└── model/
    ├── main.py
    ├── model.pkl
    └── scaler.pkl
```

## Getting Started

### 1. Install Dependencies

Install the required Python packages:

```sh
pip install -r requirements.txt
```

### 2. Train the Model

Run the model training script to generate the model and scaler files:

```sh
python model/main.py
```

### 3. Launch the App

Start the Streamlit app:

```sh
streamlit run App/main.py
```

## Usage

- Use the sidebar sliders to input cell nuclei measurements.
- View the radar chart for a visual summary of your inputs.
- See the predicted diagnosis and probability scores in the main panel.

## Notes

- This app is intended for use by medical professionals and should not be used as a substitute for professional medical advice, diagnosis, or treatment.

## License

This project is for educational purposes.
