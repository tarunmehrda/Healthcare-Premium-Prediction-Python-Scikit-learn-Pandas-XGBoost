<div align="center">

# 🏥 Healthcare Premium Prediction

<img src="https://github.com/user-attachments/assets/86fed22a-062b-4670-ab13-294ece6f0c43" alt="Healthcare Premium Predictor" width="800"/>

### *An intelligent machine learning system to predict health insurance premiums based on individual health and demographic factors*

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-00979D?style=for-the-badge)](https://xgboost.readthedocs.io/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Usage](#-usage) • [Technologies](#️-technologies) • [Contributing](#-contributing)

</div>

---

## 📋 Overview

The **Healthcare Premium Prediction** system leverages advanced machine learning algorithms to accurately predict health insurance costs. By analyzing multiple factors including age, medical history, lifestyle, and demographics, it helps:

- 🏢 **Insurance companies** optimize pricing strategies
- 👥 **Individuals** estimate their insurance premiums accurately
- 📊 **Analysts** understand premium determinants

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎯 **Accurate Predictions**
ML-powered cost estimation using XGBoost algorithm for precise results

### 📊 **Multi-factor Analysis**
Considers 12+ parameters for comprehensive assessment

### 🎨 **User-friendly Interface**
Clean, intuitive web interface built with Streamlit

</td>
<td width="50%">

### ⚡ **Real-time Calculation**
Instant premium predictions with a single click

### 📈 **Data-driven Insights**
Based on extensive historical insurance data

### 🔒 **Privacy-focused**
No personal data storage or tracking

</td>
</tr>
</table>

---

## 🖥️ Demo

<div align="center">

<img src="https://github.com/user-attachments/assets/9341551d-3040-41d3-87cb-aef0f13d4cfe" alt="Application Interface" width="700"/>

### **Comprehensive Input Parameters**

<img src="https://github.com/user-attachments/assets/5afc4b94-1796-427f-866a-279f712ca7d7" alt="Prediction Results" width="700"/>

</div>

### 📝 Input Categories

| Category | Features |
|----------|----------|
| 👤 **Demographics** | Age, Gender, Marital Status, Region |
| 🏥 **Health Metrics** | BMI Category, Medical History, Genetic Risk |
| 🚬 **Lifestyle** | Smoking Status, Employment Status |
| 💰 **Financial** | Income, Number of Dependents |
| 📋 **Coverage** | Insurance Plan Type (Bronze/Silver/Gold) |

---

## 🚀 Installation

### Prerequisites

```bash
Python 3.8 or higher
pip package manager
```

### Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/tarunmehrda/Healthcare-Premium-Prediction-Python-Scikit-learn-Pandas-XGBoost.git

# 2. Navigate to project directory
cd Healthcare-Premium-Prediction-Python-Scikit-learn-Pandas-XGBoost

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the application
streamlit run main.py
```

### 🌐 Access the Application

Open your browser and navigate to: **http://localhost:8501**

---

## 💡 Usage

### Example Prediction

```python
# Sample Input Parameters
age = 18
dependents = 0
income = 0
genetic_risk = 0
insurance_plan = "Bronze"
employment_status = "Freelancer"
gender = "Male"
marital_status = "Married"
bmi_category = "Overweight"
smoking_status = "Regular"
region = "Northwest"
medical_history = "High blood pressure"

# Output
predicted_cost = 5475  # Annual premium in currency units
```

### 🎯 How It Works

```mermaid
graph LR
    A[User Input] --> B[Feature Engineering]
    B --> C[XGBoost Model]
    C --> D[Premium Prediction]
    D --> E[Display Results]
```

---

## 📊 Model Architecture

### Machine Learning Pipeline

```
📥 Data Collection → 🔧 Feature Engineering → 🤖 Model Training → ✅ Validation → 🚀 Deployment
```

### Algorithms & Tools

<table>
<tr>
<td align="center" width="25%">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="60"/><br/>
<b>Scikit-learn</b><br/>
Preprocessing & Scaling
</td>
<td align="center" width="25%">
<img src="https://raw.githubusercontent.com/dmlc/dmlc.github.io/master/img/logo-m/xgboost.png" width="60"/><br/>
<b>XGBoost</b><br/>
Primary Prediction Model
</td>
<td align="center" width="25%">
<img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width="60"/><br/>
<b>Pandas</b><br/>
Data Manipulation
</td>
<td align="center" width="25%">
<img src="https://streamlit.io/images/brand/streamlit-mark-color.png" width="60"/><br/>
<b>Streamlit</b><br/>
Web Interface
</td>
</tr>
</table>

### 📈 Model Performance

- ✅ **High Accuracy**: Validated on extensive datasets
- 📊 **12+ Features**: Carefully selected parameters
- ⚙️ **Optimized**: Hyperparameter tuning for best results
- 🎯 **Robust**: Handles diverse input scenarios

---

## 📁 Project Structure

```
Healthcare-Premium-Prediction/
│
├── 📄 main.py                    # Streamlit application
├── 🔮 prediction_helper.py       # ML model & prediction logic
├── 📦 artifacts/                 # Saved models & encoders
│   ├── model.pkl
│   └── encoders/
├── ⚙️ .idea/                     # IDE configuration
├── 🗂️ __pycache__/               # Python cache
├── 📋 requirements.txt           # Python dependencies
└── 📖 README.md                  # Documentation
```

---

## 🛠️ Technologies

<div align="center">

| Technology | Purpose | Version |
|:----------:|---------|:-------:|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Core Language | 3.8+ |
| ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) | ML Framework | Latest |
| ![XGBoost](https://img.shields.io/badge/XGBoost-00979D?style=flat-square) | Gradient Boosting | Latest |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) | Data Analysis | Latest |
| ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) | Web Interface | Latest |

</div>

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn and create! Any contributions you make are **greatly appreciated**.

### How to Contribute

1. 🍴 Fork the Project
2. 🌿 Create your Feature Branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. 💾 Commit your Changes
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. 📤 Push to the Branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. 🔃 Open a Pull Request

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

<div align="center">

### **Tarun Mehrda**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tarunmehrda)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tarunmehrda)

</div>

---

## 🙏 Acknowledgments

- 🏥 Healthcare insurance industry data providers
- 💻 Open-source ML community
- 🤝 Contributors and testers
- 📚 Python and ML libraries maintainers

---

<div align="center">

### 💝 Made with ❤️ by Tarun Mehrda

#### ⭐ **Star this repository if you find it helpful!** ⭐

[![Star on GitHub](https://img.shields.io/github/stars/tarunmehrda/Healthcare-Premium-Prediction-Python-Scikit-learn-Pandas-XGBoost?style=social)](https://github.com/tarunmehrda/Healthcare-Premium-Prediction-Python-Scikit-learn-Pandas-XGBoost)

---


</div>
