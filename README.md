# 🏏 IPL Win Predictor

A simple and interactive web app built using **Streamlit** that predicts the **winning probability of an IPL team** during a match using a trained machine learning model.

---

## ✅ Features

- Predicts win probability based on live match inputs  
- Dynamic team selection with validation (batting ≠ bowling)  
- Selectable venue from official IPL stadiums  
- Inputs for target, score, overs completed, and wickets fallen  
- Responsive and clean user interface using Streamlit  

---

## 🛠 Technologies Used

- **Python** – Core programming language  
- **Streamlit** – For building the web UI  
- **Pandas** – Data manipulation  
- **Scikit-learn** – Machine learning pipeline  
- **Pickle** – Model serialization  

---

## ⚙️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/EndravathKrishna/IPL-Win-Predictor.git
cd IPL-Win-Predictor

# 2. (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# 3. Install required Python packages
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
