# 98-accuracy-airbnb-price-prediction-

This project aims to build a robust machine learning model that predicts Airbnb listing prices based on features like room type, property type, number of accommodates, amenities, and more. The system achieves 98% accuracy on the test set, showcasing strong predictive performance.

Rows:74112
Columns : id,log_price,property_type,room_type,amenities,accommodates,bathrooms,bed_type,cancellation_policy,cleaning_fee,city,description,first_review,host_has_profile_pic,host_identity_verified,host_response_rate host_since,instant_bookable,last_review,latitude,longitude,name,neighbourhood,number_of_reviews,review_scores_rating,thumbnail_url,zipcode,bedrooms,beds.

since the dataset is of 50 mb. So , it is compressed and kept as train.7z

🛠️ Features
Data cleaning & preprocessing
Null value handling
Label Encoding for categorical variables
Skewness correction using PowerTransformer (yeo-)
Exploratory Data Analysis (EDA)
Feature importance using correlation & plots
Model training using XGBoostRegressor
Cross-validation using KFold
Accuracy: 98%
Prediction on new/unseen data

⚙️ Tech Stack
Language: Python
Libraries:
  Pandas, NumPy
  Seaborn, Matplotlib
  Scikit-learn
  XGBoost




