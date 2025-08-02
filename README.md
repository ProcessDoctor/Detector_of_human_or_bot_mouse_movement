# Detector_of_human_or_bot_mouse_movement
This project demonstrates the use of machine learning to classify human vs bot sessions based on mouse pointer events. The project utilizes Random Forest Classifier and engineered features such as velocity, inter-event timing, direction entropy, and more.

Technologies Used
Python 3.x

Libraries: NumPy, Pandas, Matplotlib, Scikit-learn

Machine Learning: Random Forest Classifier from Scikit-learn

Objective
Simulate human-like and bot-like mouse movements.

Extract relevant features (e.g., speed, timing, entropy) from the movement patterns.

Classify the sessions using Random Forest and evaluate the model's performance.

Key Features
Data Simulation: 50 human and 50 bot sessions were simulated with mouse path generation techniques.

Feature Engineering: Features like velocity, inter-event timing, direction entropy, and movement smoothness were derived from the movement data.

Classification: A Random Forest Classifier was used to classify sessions as human or bot.

Evaluation: The model's performance was evaluated using confusion matrix, classification report, and ROC-AUC.

How to Run
Clone this repository:

bash
Copy
git clone https://github.com/yourusername/bot-human-classification.git
Install the required dependencies:

bash
Copy
pip install -r requirements.txt
Run the script to generate data, train the model, and evaluate:

bash
Copy
python main.py
Results
The model was able to classify human vs bot movements with high accuracy.

Performance metrics include confusion matrix, classification report, and ROC-AUC.

Output Example
Confusion Matrix: Shows the classification accuracy on test data.

ROC Curve: Displays the model's ability to distinguish between classes.

Repository Contents
main.py: Script to generate the data, train the model, and evaluate.

data_simulation.py: Simulated data generation functions.

feature_engineering.py: Functions for feature extraction.

requirements.txt: List of dependencies.
