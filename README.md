# Telecom Analytics

A data analytics project for analyzing telecommunications network data, including user behavior, application usage patterns, and network performance metrics.

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## 🎯 Project Overview

This project focuses on cleaning, exploring, and analyzing telecommunications data to extract meaningful insights about user behavior, network usage patterns, and application-specific consumption (YouTube, Netflix, Gaming, etc.).

**Key Features:**
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- User behavior analysis
- Application usage pattern identification
- Network performance metrics analysis

## 📁 Project Structure

```
telecomAnalytics/
│
├── data/                       # Datasets
│   └── Field Descriptions.xlsx
│
├── notebooks/                  # Jupyter notebooks
│   └── Data_Exploration.ipynb # Main data exploration notebook
│
├── scripts/                    # Python modules
│   └── script.py              # Utility functions
│
├── models/                     # Trained models
│   └── model.pkl
│
├── tests/                      # Unit tests
│   └── test_script.py
│
├── requirements.txt            # Python dependencies
├── setup.py                    # Package setup
└── README.md
```

## 🚀 Installation

### Prerequisites

- Python 3.6+
- pip

### Setup

1. **Clone the repository**
   ```bash
   git clone git@github.com:Kamuzinzi/telecomAnalytics.git
   cd telecomAnalytics
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   pip install -e .
   ```

## 💻 Usage

1. **Data Exploration:** Open `notebooks/Data_Exploration.ipynb` to explore the telecom dataset
2. **Run Scripts:** Use modules in `scripts/` for data processing and analysis
3. **Run Tests:** Execute `pytest tests/` to run unit tests

### Example Usage

```python
from scripts.script import find_average, count_occurence

# Calculate average
data = [0, 0, 9, 0, 8, 9, 0, 7]
avg = find_average(data)

# Count occurrences
counts = count_occurence(data)
```

## 🛠️ Technologies Used

- **Python 3.6+**
- **Data Processing:** pandas, numpy
- **Visualization:** matplotlib, seaborn, plotly
- **Machine Learning:** scikit-learn
- **Testing:** pytest

## 📊 Data Fields

The dataset includes telecommunications network data with fields such as:
- **Bearer Id**: Unique identifier for data sessions
- **IMSI**: International Mobile Subscriber Identity
- **MSISDN/Number**: Mobile phone number
- **IMEI**: International Mobile Equipment Identity
- **Application Usage**: YouTube, Netflix, Gaming, and other application data usage (Download/Upload bytes)
- **Network Metrics**: Duration, location, and performance data

---

⭐ If you find this project helpful, please consider giving it a star!
