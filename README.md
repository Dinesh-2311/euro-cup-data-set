# uefa-euro-prediction

**UEFA Euro Prediction Model**
This project aims to predict the outcomes of UEFA Euro matches using a Poisson distribution-based model. The model uses historical data to predict the number of goals each team is likely to score and then calculates the probabilities of different match outcomes (win, draw, loss) based on these predictions.

**Table of Contents**
Introduction
Requirements
Installation
Usage
Model Details
Results
License

**Introduction**:
The project involves simulating each game in the UEFA Euro to find the most likely results. The model uses Poisson distribution to predict the number of goals each team will score based on historical data. The predictions are then used to determine the probabilities of different match outcomes.

**Requirements**:
Python 3.x
pandas
numpy
matplotlib
seaborn
scipy
tqdm

**Installation**
Clone the repository:git clone https://github.com/Dinesh-2311/euro-cup-data-set.git
 uefa-euro-prediction
 
**Install the required packages:** pip install -r requirements.txt

**Usage**: Ensure you have the necessary data files in the data directory:
new_model.csv
euro_matches.csv

**Run the Jupyter notebook to perform the predictions:**
**jupyter notebook Final_Prediction.ipynb**
Follow the instructions in the notebook to load the data, train the model, and predict match outcomes.

**Model Details**
The model uses the following steps to predict match outcomes:

**Data Loading:** Load historical match data and team statistics.

**Feature Extraction:** Extract features for each team based on historical performance.

**Model Training:** Train a Random Forest model to predict the expected goals (xG) for each team.

**Poisson Distribution:** Use the Poisson distribution to calculate the probabilities of different goal outcomes.

**Match Simulation:** Simulate each match to determine the most likely outcome based on the calculated probabilities.

**Results**
The model outputs the probabilities of each team winning, drawing, or losing, along with the most probable scoreline for each match. The results are displayed in a formatted table and visualized using bar charts.

Example output:
Germany Wins: 59.10%
Draw: 29.18%
Scotland Wins: 11.71%
most prob result Germany 2 - 1 Scotland

**License**:
This project is licensed under the MIT License. See the LICENSE file for details.

