# END-TO-END-DATA-SCIENCE-PROJECT

COMPANY: CODTECH IT SOLUTIONS

NAME: SUSHMITHA PS

INTERN ID: CT04DG1440

DOMAIN: DATA SCIENCE

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH

This comprehensive data science project demonstrates the end-to-end process of building and deploying a machine learning model for California house price prediction. The project began with data collection, leveraging the readily available California Housing dataset from Scikit-learn, negating the need for complex web scraping. The subsequent data preprocessing and model training phase was meticulously carried out in a Jupyter Notebook (ideal for iterative development and visualization). This involved essential steps such as Exploratory Data Analysis (EDA) to understand data distributions and correlations, followed by crucial data cleaning (though minimal for this clean dataset) and feature engineering. A key step was feature scaling using StandardScaler to normalize numerical features, preparing the data for the machine learning algorithm. For model selection, a LinearRegression model was chosen and trained on the preprocessed data. Model performance was then rigorously evaluated using metrics like RMSE and R-squared. Crucially, both the trained LinearRegression model and the fitted StandardScaler were then persisted (saved) using joblib for later use in the deployment phase, ensuring that new, incoming data could be transformed consistently before prediction. The final and pivotal stage was model deployment, where a RESTful API was built using the Flask web framework. This Flask application loads the saved model and scaler, provides a /predict endpoint that accepts house features in JSON format, preprocesses them using the loaded scaler, makes a prediction, and returns the predicted house price. This API allows external applications or users to programmatically interact with the machine learning model. For actual public access, such an API would typically be deployed on cloud platforms like Heroku, AWS, or Google Cloud, which handle the infrastructure and ensure continuous availability. The entire process showcases a practical workflow from raw data acquisition and model development to making the intelligence accessible via a web service.

#output

<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/18d826b2-9017-49d8-bb91-13866ece14d0" />
<img width="1918" height="1017" alt="Image" src="https://github.com/user-attachments/assets/59c371ed-e2df-45d0-b2c3-07cf6fb611f3" />
<img width="1915" height="1064" alt="Image" src="https://github.com/user-attachments/assets/cc0468f1-4da0-4b36-9219-dd77f8be6bb9" />
<img width="1915" height="1067" alt="Image" src="https://github.com/user-attachments/assets/0ce82516-75e0-456e-94d4-3fca5dae596f" />
<img width="1806" height="365" alt="Image" src="https://github.com/user-attachments/assets/6caa4b15-d9a4-4dae-920a-b6e407202425" />
