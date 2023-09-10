


# Banknote Authentication: From Image to Insight

### Overview

This project delves into the captivating domain of banknote authentication. Using detailed images of genuine and forged banknotes as a foundation, we traverse the process of image transformation, data visualization, and machine learning modeling to discern the authenticity of banknotes.

### Table of Contents

- [Dataset Description](#dataset-description)
- [Transformation Journey](#transformation-journey)
- [Modeling and Results](#modeling-and-results)
- [Key Learnings](#key-learnings)
- [Technologies Used](#technologies-used)

### Dataset Description

The core dataset comprises high-resolution 400x400 pixel images of banknotes, both genuine and forged. Each image encapsulates various features and nuances crucial to the authentication process.

### Transformation Journey

1. **Wavelet Transformers**: A technique employed to convert raw images into quantifiable metrics. The transformed data encompasses four distinct components: variance, skewness, kurtosis, and entropy.
  
2. **Visual Deep Dive**: Post-transformation, a detailed analysis illuminated data distributions and potential correlations within the dataset.

3. **Pre-processing**: Utilized Principal Component Analysis (PCA) to optimize features and pave the way for modeling.

### Modeling and Results

Three machine learning models were explored:
- XGBoost
- Logistic Regression
- K-Nearest Neighbors

Each model demonstrated a commendable accuracy, reinforcing the strength and reliability of the preprocessing and transformation steps.

### Key Learnings

- Grasped the intricacies of converting intricate images into actionable data.
- Realized the importance of bespoke feature extraction and its optimization.
- Encountered the challenges and rewards of strategic model selection.

### Technologies Used

- Python
- Pandas
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
