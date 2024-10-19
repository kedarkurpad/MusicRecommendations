# Music Recommendation System

This repository contains a **recommendation system project** based on a partially completed `.ipynb` template provided by **MIT/Great Learning**. The project leverages **song metadata and user behavior** to suggest songs tailored to user preferences. Systems like these can **boost engagement** by helping users navigate vast content libraries more effectively.

## Technologies Used  
- **Python** (scikit-learn, Pandas, NumPy)  
- **Jupyter Notebooks**  

## Data Summary  
The dataset consists of:  
- **Song Data:** Titles, release years, and artist information.  
- **User Data:** User IDs, song IDs, and play counts.  

After **data cleaning and preparation**, the working dataset includes:  
- 400,730 entries  
- 3,156 unique users  
- 9,998 unique songs  
- 3,374 unique artists  

## Features  
- **Collaborative Filtering:** Predict user preferences based on similar users, achieving an optimized RMSE of **1.0529**.  
- **Matrix Factorization Models:** Improve accuracy by decomposing the user-item interaction matrix, optimized RMSE of **1.019**.  
- **Hyperparameter Tuning:** Use **GridSearchCV** from scikit-learn to optimize model performance.

## Known Issues / Maintenance  
- **User-Item Collaborative Filtering:**  
  The current collaborative filtering model returns **unexpectedly high RMSE values (>5)**. Further investigation is needed to diagnose potential causes, such as **data sparsity, hyperparameter issues, or matrix factorization errors**.  

- **Dataset Availability:**  
  Initial development was conducted in **Google Colab** using **Google Drive-hosted datasets**. To improve accessibility, the plan is to integrate a **lighter-weight dataset directly into this repository** for easier use and reproducibility.

## Next Steps / Future Development  
- **Enhance collaborative filtering performance:** Identify and address the root cause of high RMSE values.  
- **Incorporate content-based filtering:** Add content-based recommendations to complement collaborative filtering models.  
- **Experiment with additional datasets:** Explore publicly available datasets to improve model robustness.  
- **Refactor code for modularity:** Organize the codebase into reusable modules for easier maintenance.  
- **Deploy as a Streamlit app:** Create a user-friendly interface to interact with the recommendation system.

## Contact  
- **GitHub:** [@kedarkurpad](https://github.com/kedarkurpad)  
- **LinkedIn:** [Kedar Kurpad](https://linkedin.com/in/kedar-kurpad) 
