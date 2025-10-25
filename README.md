# Laptop-Price-Prediction

Description: Developed a machine learning model to predict laptop prices based on hardware specifications, enabling better understanding of key factors influencing product pricing and assisting in price estimation for new laptops.

Loaded and explored the dataset to assess data quality, handle missing values, and remove irrelevant columns.

Cleaned and transformed numerical features such as RAM, Weight, and Memory for consistency.

Engineered new features including Touch Screen, IPS, PPI, SSD, and HDD from existing attributes to improve model accuracy.

Performed exploratory data analysis (EDA) using Seaborn and Matplotlib to visualize relationships between specifications and laptop prices.

Applied One-Hot Encoding on categorical columns (Company, TypeName, Processor, GPU Name, OS) using make_column_transformer and make_pipeline for streamlined preprocessing.

Trained and evaluated Linear Regression and Lasso Regression models using R² score, achieving an R² of 0.71 on the test set.

Derived insights into the most influential features affecting laptop prices, such as brand and hardware configuration.

Tech Stack: Python, pandas, scikit-learn, Seaborn, Matplotlib
