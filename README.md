##Electric Motor Temperature Prediction Using Machine Learning
## Project Overview
This project focuses on predictive maintenance by forecasting the temperature of electric motors in industrial settings using machine learning. By analyzing historical operational data such as motor load, voltage, current, and environmental factors, the model predicts motor temperatures to prevent overheating, avoid failures, optimize maintenance schedules, and enhance operational efficiency.
## Use Cases
- **Preventive Maintenance:** Enables timely maintenance by predicting potential overheating, thus reducing downtime and costly failures.
- **Energy Efficiency:** Helps optimize energy usage by keeping motors at optimal temperatures.
- **Equipment Reliability:** Enhances reliability and lifespan of motors in critical industries like automotive production and HVAC.
### Objectives:
- Understand problem type (regression/classification).
- Perform data preprocessing (cleaning, handling outliers, categorical data, etc.).
- Build and evaluate multiple ML models.
- Develop a Flask-based web application for user interaction and prediction display.
##Machine Learning Models Used
    Linear Regression
    Decision Tree
    Random Forest
    Support Vector Machine (SVM)
The models are trained on historical sensor data such as motor speed, torque, current, voltage, and environmental parameters.
## Technologies Used
    Programming Language: Python
    Machine Learning: Scikit-learn, NumPy, Pandas
    Web Interface: HTML, CSS
    Backend: Flask
    Visualization: Matplotlib / Seaborn
### Project Workflow:
1. **Data Collection:** Gather or create relevant datasets.
2. **Data Analysis:** Conduct univariate, multivariate, and descriptive analysis.
3. **Data Pre-processing:** Clean data, handle null values and outliers, encode categorical data, and address imbalances.
4. **Model Building:** Train, test, evaluate, and save predictive models.
5. **Application Development:** Create a user interface with HTML and integrate the ML model in Python using Flask.

## Dataset & Models
- Dataset: `measures_v2.csv` (not included due to size limits).
- Models: Generated locally via `train_model.py` and `sensor_model_train.py`.

## How to Run the Project
```bash
git clone https://github.com/Geethika-dasi/Electric_Motor_Project.git
pip install -r requirements.txt
python app.py
```
Access the web app at http://127.0.0.1:5000

## Applications
- Industrial motor monitoring
- Predictive maintenance systems
- Electric vehicle management
- Smart manufacturing
- Automation industries

## Future Enhancements
- Real-time sensor integration
- Cloud deployment
- Advanced deep learning models
- Live dashboards and analytics

## Conclusion
This project illustrates the effective use of machine learning for predicting electric motor temperature in industrial environments, aiding in reducing downtime, preventing failures, and improving efficiency through predictive maintenance.
