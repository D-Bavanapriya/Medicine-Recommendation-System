# Medicine-Recommendation-System
# Overview
The Medicine Recommendation System is an intelligent application designed to assist users in identifying potential diseases based on their symptoms and provide corresponding medicine recommendations. By leveraging machine learning techniques, the system aims to enhance healthcare accessibility and decision-making.

# Features
* Symptom-Based Diagnosis: Users can input their symptoms, and the system predicts possible diseases.

* Medicine Recommendations: For each predicted disease, the system suggests appropriate medications.

* Additional Health Guidance: Offers dietary suggestions, workout plans, and precautions related to the diagnosed condition.

* User-Friendly Interface: An intuitive web interface built using HTML for seamless user interaction.

# Dataset
The system utilizes several datasets to function effectively:

* Training.csv: Contains training data mapping symptoms to diseases.

* Symptom-severity.csv: Details the severity level of various symptoms.

* Medications.csv: Lists medicines associated with different diseases.

* Diets.csv: Provides dietary recommendations for various conditions.

* Workout_df.csv: Suggests workout plans tailored to specific diseases.

* Precautions_df.csv: Enumerates precautions to be taken for different ailments.

* Description.csv: Offers detailed descriptions of diseases.

* Symptoms_df.csv: Contains a comprehensive list of symptoms.

# Technologies Used
- Machine Learning: Implements algorithms (e.g., Support Vector Machine) for disease prediction.

- Python: Core programming language for backend development.

- Jupyter Notebook: Used for model training and experimentation.

- HTML: Structures the frontend interface.

- Pickle (svc.pkl): Stores the trained machine learning model for deployment.

# Installation & Usage
Clone the Repository:

git clone https://github.com/D-Bavanapriya/Medicine-Recommendation-System.git

Navigate to the Project Directory:

cd Medicine-Recommendation-System

Install Required Dependencies: Ensure you have Python installed. Then, install necessary packages:

pip install -r requirements.txt
Run the Application: Execute the main Python script:

python main.py
Access the Interface: Open index.html in your web browser to interact with the system.
