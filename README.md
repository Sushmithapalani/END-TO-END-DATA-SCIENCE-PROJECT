# END-TO-END-DATA-SCIENCE-PROJECT

COMPANY: CODTECH IT SOLUTIONS

NAME: SUSHMITHA PS

INTERN ID: CT04DG1440

DOMAIN: DATA SCIENCE

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH

This comprehensive data science project demonstrates the end-to-end process of building and deploying a machine learning model for California house price prediction. The project began with data collection, leveraging the readily available California Housing dataset from Scikit-learn, negating the need for complex web scraping. The subsequent data preprocessing and model training phase was meticulously carried out in a Jupyter Notebook (ideal for iterative development and visualization). This involved essential steps such as Exploratory Data Analysis (EDA) to understand data distributions and correlations, followed by crucial data cleaning (though minimal for this clean dataset) and feature engineering. A key step was feature scaling using StandardScaler to normalize numerical features, preparing the data for the machine learning algorithm. For model selection, a LinearRegression model was chosen and trained on the preprocessed data. Model performance was then rigorously evaluated using metrics like RMSE and R-squared. Crucially, both the trained LinearRegression model and the fitted StandardScaler were then persisted (saved) using joblib for later use in the deployment phase, ensuring that new, incoming data could be transformed consistently before prediction. The final and pivotal stage was model deployment, where a RESTful API was built using the Flask web framework. This Flask application loads the saved model and scaler, provides a /predict endpoint that accepts house features in JSON format, preprocesses them using the loaded scaler, makes a prediction, and returns the predicted house price. This API allows external applications or users to programmatically interact with the machine learning model. For actual public access, such an API would typically be deployed on cloud platforms like Heroku, AWS, or Google Cloud, which handle the infrastructure and ensure continuous availability. The entire process showcases a practical workflow from raw data acquisition and model development to making the intelligence accessible via a web service.
