# Health Risk Assessment Dashboard

![License](https://img.shields.io/github/license/Akshat-Sh101/Health-Risk-Assessment-Dashboard)
![Python](https://img.shields.io/badge/Python-3.8+-blue)

## Overview
The Health Risk Assessment Dashboard is a web-based application that leverages machine learning to assess and visualize health risks based on user-provided data. Designed for healthcare providers, insurers, or individuals, it offers an intuitive interface to input health metrics and view predictive risk scores through interactive visualizations.

## Features
- **Interactive Visualizations**: Dynamic charts and graphs powered by Chart.js for risk insights.
- **Machine Learning Models**: Predict health risks using Logistic Regression and Support Vector Machine (SVM) algorithms.
- **Data Input**: User-friendly forms for entering health parameters (e.g., age, medical history, lifestyle).
- **Responsive Design**: Accessible on desktop and mobile devices.
- **Exportable Results**: Save or export risk assessment reports.

## Technologies Used
- **Frontend**: React.js, HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **Machine Learning**: Scikit-learn (Logistic Regression, Support Vector Machine), NumPy, Pandas
- **Other Tools**: Git

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Akshat-Sh101/Health-Risk-Assessment-Dashboard.git
   cd Health-Risk-Assessment-Dashboard
   ```

2. **Install Frontend Dependencies**:
   ```bash
   npm install
   ```

3. **Install Backend Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   - Start the backend:
     ```bash
     python app.py
     ```
   - Start the frontend:
     ```bash
     npm start
     ```

5. **Access the Dashboard**:
   Open `http://localhost:3000` in your browser.

## Usage
1. Launch the application and navigate to the dashboard.
2. Input health data (e.g., age, blood pressure, cholesterol levels) via forms.
3. The backend processes data using Logistic Regression or SVM models to predict health risks.
4. View results in interactive charts and NumPy-based data processing.
5. Export reports for further analysis.

## Machine Learning Implementation
- **Logistic Regression**: Used for binary classification of health risks (e.g., high/low risk).
- **Support Vector Machine (SVM)**: Employed for complex, non-linear risk prediction tasks.
- **NumPy & Pandas**: Handle data preprocessing, feature engineering, and numerical computations.
- Models are trained on sample health datasets (e.g., synthetic or open-source health data).

## Contributing
1. Fork the repository.
2. Create a branch: `git checkout -b feature-branch`.
3. Commit changes: `git commit -m "Add feature"`.
4. Push: `git push origin feature-branch`.
5. Open a pull request with a detailed description.

## License
MIT License. See [LICENSE](LICENSE) for details.

## Contact
For inquiries, contact [Akshat-Sh101](https://github.com/Akshat-Sh101) or open an issue on [GitHub](https://github.com/Akshat-Sh101/Health-Risk-Assessment-Dashboard/issues).

## Acknowledgments
- Scikit-learn for ML model implementation
- Chart.js for data visualization
- Open-source health datasets 
