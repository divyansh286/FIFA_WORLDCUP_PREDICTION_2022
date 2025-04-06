# 🏆 FIFA World Cup 2022 – Data Analysis & Match Outcome Prediction

This project performs a detailed data-driven analysis of the FIFA World Cup 2022, combining **web scraping**, **visual analytics**, and **match prediction** using Logistic Regression.

## 📌 Project Objective

- To analyze team performance and group outcomes in the 2022 World Cup
- To build a basic predictive model to estimate match results
- To visualize tournament progression and highlight top-performing nations

## 📊 Features & Workflow

### 🔍 1. Data Collection
- Scraped team data and group standings from [Wikipedia](https://en.wikipedia.org/wiki/2022_FIFA_World_Cup)
- Used `pandas.read_html()` and `BeautifulSoup` to automate extraction
- Gathered missing knockout-stage data manually

### 🧹 2. Data Cleaning & Preparation
- Cleaned group-wise match results and formatted team names
- Combined datasets into one match-level record
- Built data dictionaries for visualizing groups

### 📈 3. Exploratory Data Analysis
- Analyzed group performance
- Visualized team-wise win/loss/draw stats
- Evaluated goal differences and rankings

### 🧠 4. Predictive Modeling

#### Model: `Logistic Regression`
- **Reason for Use**: Simple and interpretable; effective for classification tasks involving match outcome prediction
- **Features**:
  - Historical match results
  - Team statistics (goals scored, conceded, etc.)
  - Group ranks and stage positions
- **Output**: Predicted Win/Draw/Loss for selected matches

## 🔗 Project Structure

- `sport_anlysis.ipynb`: Complete code for data scraping, processing, and modeling
- `data/`: (Optional) Local storage for intermediate CSVs or results
- `sport_anlysis_Report.pdf`: Final report with graphs and interpretations

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- BeautifulSoup
- Scikit-learn (Logistic Regression)
- Seaborn, Matplotlib

## 📈 Results

- Successfully scraped and processed all group/knockout data
- Developed a functional predictive model for match outcomes
- Visualized overall tournament dynamics

## 👤 Author

- **Divyansh Dwivedi**

## 📜 License

This project is licensed under the MIT License.



