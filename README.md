**GitHub README.md Summary for Electric Motor Temperature Prediction Project**

---

# Electric Motor Temperature Prediction using Machine Learning

## Project Description
This project implements a machine learning-based predictive maintenance system to forecast electric motor temperatures in industrial environments. By using historical sensor data such as motor speed, torque, current, voltage, and environmental parameters, the models predict motor temperatures to prevent overheating, enhance equipment reliability, reduce downtime, and optimize maintenance schedules.

## Key Scenarios
- **Preventive Maintenance:** Schedule timely inspections and replacements by anticipating overheating issues.
- **Energy Efficiency:** Optimize motor operations to reduce energy consumption and operational costs.
- **Equipment Reliability:** Ensure motors operate within safe temperatures to extend lifespan and minimize breakdowns.

## Machine Learning Models Used
- Linear Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## Technologies
- Programming Language: Python
- Machine Learning Libraries: Scikit-learn, NumPy, Pandas
- Web Interface: HTML, CSS
- Backend Framework: Flask
- Visualization Tools: Matplotlib, Seaborn

## Project Objectives
- Understand problem type: regression vs. classification
- Perform data preprocessing (cleaning, handling outliers, categorical & imbalanced data)
- Train and evaluate various ML algorithms
- Build a Flask web application for input and prediction display

## Workflow
1. User inputs sensor data via UI.
2. Integrated ML model processes inputs.
3. Predicted motor temperature is displayed on UI.

## Project Steps
- Data collection or creation
- Data visualizations and analysis (univariate, multivariate, descriptive)
- Data preprocessing (feature selection, null values handling, outlier removal, data splitting)
- Model initialization, training, testing, evaluation, and saving
- Web application creation using Flask and HTML

## Dataset & Model Files
- Dataset: `measures_v2.csv` (not included due to size constraints)
- Model files (`.pkl`) are generated locally via:
  ```bash
  python train_model.py
  python sensor_model_train.py
  ```

## Running the Project

```bash
git clone https://github.com/Geethika-dasi/Electric_Motor_Project.git
pip install -r requirements.txt
python app.py
```

Access the application on: http://127.0.0.1:5000

## Applications
- Industrial motor monitoring
- Predictive maintenance systems
- Electric vehicle motor temperature management
- Smart manufacturing
- Automation industry monitoring

## Future Enhancements
- Real-time sensor data integration
- Cloud deployment
- Advanced deep learning models
- Live dashboards and analytics visualization

## Conclusion
This project highlights the practical utility of machine learning in forecasting electric motor temperature, enabling industries to improve operational efficiency, reduce failure risks, and implement proactive maintenance effectively.

---

If you want, I can also help you create this summary as a formatted `README.md` file for GitHub.
