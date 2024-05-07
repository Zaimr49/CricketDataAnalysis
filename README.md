# 🏏 Batting Through Numbers: A Data-Driven Analysis of Cricket

Welcome to our repository where data meets passion in the realm of cricket! This project is a detailed exploration of cricket analytics, where we use data science to uncover hidden patterns and optimize strategies.

## 🌟 Project Overview

"Batting Through Numbers" is not just about cricket analytics; it's a blend of our love for the game and statistical analysis. We delve deep into datasets to discover what lies beneath the surface of scorecards and player statistics.

## 🎯 Research Questions Addressed

1. **Association Between Batting Position and Dismissal**:
   - We investigate how a player’s batting position correlates with their likelihood of getting dismissed, providing insights that could influence batting order decisions.

2. **Distribution of Dismissal Types for Top-Scoring Batsmen**:
   - This analysis focuses on understanding how top performers typically get out, which may help coaches tailor specific training to mitigate these dismissals.

3. **Forecasting Batting Performance Using Machine Learning**:
   - By employing historical data on similar batting positions, we develop predictive models to forecast batting performances, offering a tool for strategy formulation.


## 🎯 Objectives

- **Analyzing T20 Ball-by-Ball Data**: Using detailed ESPN datasets, we uncover complex play patterns and performance metrics.
- **Predictive Modeling**: We build models to predict match outcomes for the LUMS cricket team and other international teams, leveraging historical performance data.
- **Cricket Storytelling**: Beyond numbers, we narrate stories of cricket matches, offering insights that are often overlooked.

## 📂 Repository Structure

- **models**: Contains machine learning models saved as `.pkl` files for various international cricket teams.
- **data**: Includes datasets such as:
  - `ball_by_ball_it20(train dataset).csv`: Detailed ball-by-ball play data for training our models.
  - `LUMS Cricket Dataset - Batting.csv`: Specific dataset for batting performance of the LUMS team.
  - `LUMS Cricket Dataset - Balling.csv`: Specific dataset for bowling performance of the LUMS team.
- **CricketDataAnalysis.ipynb**: Jupyter notebook containing all the analysis, from data preprocessing to model training and evaluation.

## 🔧 Tools & Technologies Used

- **Python**: For all computing and data analysis.
- **Pandas & NumPy**: For data manipulation.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-Learn**: For predictive modeling and machine learning.
- **Jupyter Notebook**: For interactive code development and testing.

## 🔧 Data Preparation and Transformation

### Data Creation

- **Data Prep**:
  - Loaded, cleaned, and simplified batting/bowling datasets.
  - Handled null values and dropped unnecessary columns.

- **Data Transformation**:
  - Developed specific functions for dataset generation.
  - Imputed numeric nulls, mapped categorical data, and standardized columns.

- **Summarized Data**:
  - Condensed ball-by-ball details into summarized player stats per match.
  - Key metrics include runs, balls faced, batting position, etc.

- **Result**:
  - Created a concise dataset focusing on player performance in matches.
  - Columns include: `batter`, `runs`, `ballsPlayed`, `howOut`, `battingPosition`, `teamName`, `batFirst`, `targetScore`, `extraRuns`, `winner`, `matchId`.

## 📈 Statistical Analysis, Results, and Key Findings

### Statistical Test
- **Chi-square statistic**: 324.20
- **P-value**: 3.84e-62

### Average Treatment Effect (ATE)
- **ATE**: 0.177
- **Inference**: Top-scoring batsmen exhibit a higher average dismissal type compared to non-top-scorers.

- **Statistical Analysis**: We performed extensive statistical tests, like the Chi-squared test, to explore the association between a player's batting position and their likelihood of dismissal.
- **Predictive Performance**: Our models, trained on diverse datasets, predict outcomes with high accuracy, demonstrated by metrics like RMSE (Root Mean Squared Error).
- **Strategic Insights**: Recommendations on batting order and player positioning that can significantly affect match outcomes.


## 🚀 How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CricketDataAnalysis.git

2. Install the necessary Python packages:
   ```bash
    pip install -r requirements.txt

3. Run the Jupyter notebooks:
   ```bash
    jupyter notebook

## 📝 Conclusion
Our project bridges the gap between raw data and actionable cricket insights. It demonstrates how data-driven strategies can be applied to enhance understanding and performance in sports analytics.

## 🤝 Contributing
Feel free to fork this repo, suggest changes via pull requests, or discuss ideas in issues. Your contributions are always welcome!

## 🌐 Contact
For any further questions, please email us at zaeemr49@gmail.com, or raise an issue in this repository.

## ⭐ Support
If you find this repository helpful, please consider giving it a star to help others find it!
