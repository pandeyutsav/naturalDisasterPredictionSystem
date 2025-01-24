### README for "Natural Disaster Predictor"

---

# 🌍 Natural Disaster Predictor 🌪️

**Natural Disaster Predictor** is a machine learning-driven web application designed to predict the likelihood of various natural disasters across U.S. states based on historical data. The project integrates a Flask-based backend for predictions and data processing with a React-based frontend for visualization and user interaction.

---

## 📖 Overview

This project provides a predictive analysis of natural disasters, enabling users to:
- Input a year and view disaster probabilities for U.S. states.
- Explore visualizations on an interactive map and bar charts.
- Access detailed state-level disaster insights for enhanced understanding.

---

## ✨ Key Features
- **Disaster Probability Prediction**: Predicts probabilities of disasters like floods, hurricanes, wildfires, etc., based on historical trends.
- **Interactive Map**: Visualizes predictions across all U.S. states on a map for easy interpretation.
- **Bar Charts and Tables**: Provides additional insights through graphical and tabular data presentations.
- **Responsive Design**: User-friendly interface designed to work seamlessly across devices.

---

## 🛠️ Tech Stack
### **Frontend**:
- React.js
- Material-UI
- Mapbox GL
- Chart.js

### **Backend**:
- Flask
- Scikit-learn
- Pandas

### **Machine Learning**:
- Support Vector Classifier (SVC)

---

## 🚀 Getting Started
### Prerequisites
- **Node.js**: [Download](https://nodejs.org/)
- **Python 3.8+**: [Download](https://www.python.org/)

---

### Installation Steps
1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd natural-disaster-predictor
   ```

2. **Backend Setup**:
   - Navigate to the server folder:
     ```bash
     cd server
     ```
   - Create a virtual environment and install dependencies:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows: venv\Scripts\activate
     pip install -r requirements.txt
     ```
   - Run the backend server:
     ```bash
     python main.py
     ```
   - The backend will run on `http://127.0.0.1:5000`.

3. **Frontend Setup**:
   - Navigate to the client folder:
     ```bash
     cd ../client
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
     ```
   - The frontend will run on `http://localhost:3000`.

4. **Update API URL**:
   - In `App.jsx`, update the `URL` constant to point to your backend:
     ```javascript
     const URL = "http://127.0.0.1:5000";
     ```

---

## 📂 Project Structure
```
natural-disaster-predictor/
│
├── client/              # Frontend code (React)
│   ├── src/
│   │   ├── components/  # React components (Map, UserInput, BarChart, etc.)
│   │   ├── App.jsx      # Main React app
│   │   └── index.css    # Styling
│   └── public/          # Static files
│
├── server/              # Backend code (Flask)
│   ├── main.py          # Entry point for Flask backend
│   ├── model.py         # Machine learning model code
│   ├── requirements.txt # Backend dependencies
│   └── processed_data/  # Processed datasets
│
└── README.md            # Project documentation
```

---

## 🖥️ Usage
1. Open your browser and go to `http://localhost:3000`.
2. Enter a year in the input field.
3. View disaster predictions on the map, bar chart, and detailed table.

---

## 🌟 Features in Action
### 1. Interactive Map
Displays disaster predictions for all U.S. states using color-coded markers.

### 2. Bar Chart Visualization
Shows the probabilities of specific disasters across states.

### 3. State-Level Table
Provides detailed insights into disaster probabilities for individual states.

---

## 🤝 Contributions
We welcome contributions! Please feel free to:
- Report bugs
- Suggest features
- Submit pull requests

For major changes, please open an issue first to discuss what you’d like to change.

---

## 📧 Contact
For any inquiries or feedback, please contact [pandeyutsav59@gmail.com]. 

--- 
