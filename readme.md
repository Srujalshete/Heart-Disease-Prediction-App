HeartNebula Pro 

![image](https://github.com/Srujalshete/Heart-Disease-Prediction-App/assets/67551839/f4dcff27-61e8-4f80-8508-306ea3e814a4)

<img width="1440" alt="home" src="https://github.com/Srujalshete/Heart-Disease-Prediction-App/assets/67551839/e015433c-f137-4e07-8677-699be7c6eff0">

This is a web application built using the Python Django framework that utilizes machine learning techniques to predict the likelihood of a person having heart disease based on various medical attributes. The application takes input from the user regarding their medical history and provides a prediction using a trained machine learning model.


Features
* User-friendly web interface for inputting medical data.
* Utilizes a pre-trained machine learning model to predict the probability of heart disease.
* Interactive visualization of results.
* Efficient and responsive design for seamless user experience.
Prerequisites
Before running the application, make sure you have the following installed:
* Python (>= 3.6)
* Django (>= 3.0)
* Required Python packages (NumPy, Pandas, Scikit-Learn)
* Virtual environment (recommended)
Installation
* Clone the repository: git clone https://github.com/yourusername/heart-disease-prediction-app.git
* Navigate to the project directory:cd heart-disease-prediction-app
* Create and activate a virtual environment:python -m venv venv.  source venv/bin/activate
Install the required packages:python manage.py runserver
* Open your web browser and navigate to http://127.0.0.1:8000/ to access the application. 
* Input the required medical attributes (e.g., age, gender, blood pressure) into the provided form. 
* Click the "Predict" button to obtain the heart disease prediction result. 
Machine Learning Model
The heart disease prediction model is trained using a dataset containing medical attributes and corresponding labels indicating the presence or absence of heart disease. The model uses advanced machine learning techniques to make predictions based on the input data.
The model is trained using the Scikit-Learn library and is serialized using joblib for integration into the Django application.

Data Privacy and Security
We take data privacy and security seriously. The medical data entered into the application is not stored or shared. The prediction is made using the provided data only, and no personal information is retained.

Contributing
Contributions to this project are welcome. Feel free to fork the repository, create a new branch, and submit a pull request for any enhancements or bug fixes.

License
This project is currently not licensed

install few python libraries before run the code
pip install pandas
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install django
pip install djangorestframework



