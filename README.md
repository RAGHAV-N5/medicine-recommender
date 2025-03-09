# Disease Diagnosis & Health Recommendation System

An AI-powered web application that predicts diseases based on user symptoms using a multiclass SVC classifier for 41-class prognosis. The system provides tailored health recommendations, including precautions, diets, workouts, and medications.

## Features
- **Disease Prediction:** Uses a multiclass SVC model trained on a dataset with **133 symptoms** and **4,920 symptom combinations**.
- **User-friendly Interface:** Built with **Streamlit** for easy symptom input and real-time classification.
- **Flask Backend:** Handles model inference and API interactions.
- **Personalized Health Recommendations:** Suggests precautions, diets, workouts, and medications based on the predicted disease.

## Tech Stack
- **Machine Learning:** scikit-learn
- **Backend:** Flask
- **Frontend/UI:** Streamlit
- **Data Processing:** pandas

## Installation & Setup

### Prerequisites
- Python 3.x
- pip

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/disease-diagnosis-system.git
   cd disease-diagnosis-system
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Flask backend:
   ```sh
   python app.py
   ```
4. Run the Streamlit UI:
   ```sh
   streamlit run app.py
   ```

## Usage
1. Open the Streamlit app in your browser.
2. Enter symptoms in the input field.
3. The system predicts the disease and displays relevant health recommendations.

## Dataset
The model was trained on a dataset containing:
- **133 unique symptoms**
- **4,920 possible symptom combinations**
- **41 different disease prognoses**

## Model Details
- **Algorithm:** Multiclass Support Vector Classifier (SVC)
- **Training Library:** scikit-learn
- **Feature Engineering:** Symptom-based feature extraction using pandas

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
