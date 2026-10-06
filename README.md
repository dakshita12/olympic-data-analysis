# 🏅 Olympics Data Analysis

An interactive web application for exploring and visualizing historical Olympic Games data using Python and Streamlit.

---

## 📌 Overview

**Olympics Data Analysis** is a data analysis and visualization project that explores historical Olympic data to identify patterns and trends in athlete participation, countries, medals, and performances.

The project uses Python-based data analysis and visualization libraries, with **Streamlit** providing an interactive interface for exploring the analysis.

---

## ✨ Features

- 🏅 **Medal Tally** — View medal counts across countries and Olympic editions.
- 📊 **Overall Analysis** — Explore overall trends and statistics from the Olympic Games.
- 🌍 **Country-wise Analysis** — Analyze the performance and medal trends of individual countries.
- 👤 **Athlete-wise Analysis** — Explore athlete-level participation and performance data.

---

## 📊 Dataset

The project uses the **120 Years of Olympic History: Athletes and Results** dataset, covering modern Olympic Games from **Athens 1896 to Rio 2016**.

The dataset contains **271,116 records and 15 columns**, where each row represents an athlete competing in an individual Olympic event.

---

## 📊 Dataset Information

|**Column**| **Description**                   |
|----------|-----------------------------------|
| `ID`     | Unique athlete identifier         |
| `Name`   | Athlete name                      |
| `Sex`    | Athlete gender                    |
| `Age`    | Athlete age                       |
| `Height` | Height in centimeters             |
| `Weight` | Weight in kilograms               |
| `Team`   | Team name                         |
| `NOC`    | National Olympic Committee code   |
| `Games`  | Olympic year and season           |
| `Year`   | Olympic year                      |
| `Season` | Summer or Winter                  |
| `City`   | Host city                         |
| `Sport`  | Sport                             |
| `Event`  | Olympic event                     |
| `Medal`  | Gold, Silver, Bronze, or no medal |

---

## 📊 Source

Dataset Link: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results

---

## 🛠️ Tech Stack

|**Technology**| **Purpose**                  |
|------------  |------------------------------|
| Python       | Core programming language    |
| Pandas       | Data cleaning and analysis   |
| NumPy        | Numerical operations         |
| Plotly       | Interactive visualizations   |
| Seaborn      | Statistical visualization    |
| Matplotlib   | Data visualization           |
| Streamlit    | Web application and dashboard|

---

## 📂 Project Structure

```text
OlympicDataAnalysis/
│
├── data/
│   ├── athlete_events.csv      # Olympic athlete and event data
│   └── noc_regions.csv         # NOC to region mapping
│
├── app.py                      # Main Streamlit application
├── helper.py                   # Analysis and visualization functions
├── preprocessor.py             # Data preprocessing and merging
├── olympic_analysis.ipynb      # EDA and analysis notebook
├── requirements.txt            # Project dependencies
├── .gitignore                  # Git ignored files
└── README.md                   # Project documentation

```
--

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/dakshita12/olympic-data-analysis
```

### 2. Navigate to the project directory
```bash
cd olympics-data-analysis
```

### 3. Create a virtual environment
```bash
python -m venv .venv
```

### 4. Activate the virtual environment
```bash
.venv\Scripts\activate
```

### 5. Install dependencies
```bash
pip install -r requirements.txt
```

### 6. Run the Application

Start the Streamlit application using:

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 📄 License

**Dataset License:** CC0: Public Domain