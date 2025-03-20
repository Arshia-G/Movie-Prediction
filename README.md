 Movie Rating Prediction

 Project Overview
This project aims to build a predictive model to estimate movie ratings based on various attributes such as genre, director success rate, actor influence, and similar movies' average ratings. The model undergoes data preprocessing, feature engineering, and evaluation to improve prediction accuracy.

 Features and Methodology
 1. Data Preprocessing
- Encoded categorical variables (Genre, Director, Actors) using numerical mappings.
- Handled missing values by imputing or dropping incomplete records.
- Removed unnecessary columns like "Duration" to avoid data type conflicts.

 2. Feature Engineering
- Director Success Rate: Computed the average rating of movies directed by each director.
- Similar Movies Rating: Calculated the average rating of movies with the same genre and lead actor.
- Added these features to the dataset to enhance predictive power.

 3. Model Training and Evaluation
- Linear Regression model was used for prediction.
- Dataset was split into train (80%) and test (20%) sets.
- Evaluated using Mean Squared Error (MSE) and visualization of actual vs. predicted ratings.

 4. Visualization and Analysis
- Scatter plot: Showed how votes affect ratings.
- Bar plot: Illustrated the top 20 directors by average success rate.
- Box plot: Displayed the distribution of votes.

 How to Run the Project
 1. Clone the Repository
bash
git clone https://github.com/your-username/movie-prediction.git
cd movie-prediction


 2. Install Dependencies
Ensure you have Python installed, then install the required libraries:
bash
pip install -r requirements.txt


 3. Run the Notebook
Open and execute the Jupyter Notebook:
bash
jupyter notebook movieprediction.ipynb


 4. View Results
- The trained model will output predicted ratings.
- Plots will provide insights into feature importance.

 Repository Structure

movie-rating-prediction/
│-- data/                Dataset files (if applicable)
│-- movieprediction.ipynb   Main Jupyter Notebook
│-- README.md            Project documentation


 Evaluation Metrics
- Mean Squared Error (MSE) for accuracy.
- Visualization comparisons to validate predictions.

 Future Improvements
- Experiment with other models like Random Forest or Neural Networks.
- Enhance feature engineering with user-based collaborative filtering.

