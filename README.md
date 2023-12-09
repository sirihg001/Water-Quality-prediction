# Water-Quality-prediction
Water quality prediction using various ML algorithms

This repository contains the final project submission for the Water Quality Prediction. This project employs machine learning to predict water potability, assessing safety through diverse quality indicators. The dataset includes pH, hardness, and chemical concentrations, forming the basis for predictive models. Addressing imbalances, ethical concerns, and feature analysis, the project contributes to proactive water quality management, aiming for global access to clean and safe drinking water.

The project employed various machine learning algorithms for classification, including Logistic Regression, Decision Tree Classifier, Random Forest Classifier, K-Nearest Neighbors (KNN), Support Vector Classifier (SVM), Naive Bayes, and XGBoost. SVM stood out for its robust performance, demonstrating superior accuracy and a balanced precision-recall trade-off compared to other models.

1.Clone the Repository:

git clone https://github.com/YourUsername/Water-Quality-Prediction.git
2.Navigate to Project Directory:

cd Water-Quality-Prediction
3.Install Dependencies:

pip install -r requirements.txt
Run the Flask App: Execute the following command to run the Flask application:
python app.py
This will start the Flask development server.

Access the Application: Open your web browser and go to http://127.0.0.1:5000/. You should see the water quality prediction form.

Input Water Quality Parameters: Fill in the values for pH, hardness, solids, chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity.

Submit the Form: Click the "Predict Potability" button to submit the form. The application will process your input and display the prediction results.

Explore Results: Review the prediction for water potability (Potable or Not Potable) based on the provided water quality parameters.

That's it! You have successfully run the Flask application and used the machine learning model to predict water potability.

The Water Quality Prediction project contributes to the intersection of data science and public health by leveraging machine learning techniques to ensure safe drinking water. The results highlight the potential of SVM for accurate water quality classification.

Feel free to explore and contribute to the project, enhancing our understanding of water quality and safety for human consumption.
