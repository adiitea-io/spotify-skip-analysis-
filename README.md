## Overview
This project analyzes user playback behavior from Spotify streaming sessions to estimate the risk of early song skipping. Using contextual features such as platform, shuffle mode, autoplay behavior, and time of day, the system identifies patterns associated with skipping behavior.

Exploratory Data Analysis (EDA) is performed to understand playback duration trends and skip behavior across different contexts. Two classification models—Logistic Regression and Random Forest—are trained and compared to predict early skips. The Random Forest model achieves approximately **83% accuracy**, **78% recall for early skips**, and an **average precision of 0.77**, demonstrating strong performance on imbalanced behavioral data.

Instead of producing only binary predictions, the model outputs probabilistic skip-risk scores, which are further segmented into Low, Medium, and High risk categories. This approach mirrors real-world recommendation systems by enabling actionable decision-making rather than simple yes/no predictions.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

 ## Key Results
- Logistic Regression and Random Forest models were evaluated
- Random Forest achieved:
  - ~83.5% Accuracy
  - ~78% Recall for early skip detection
  - 0.77 Average Precision (Precision–Recall Curve)
- Skip risk probabilities were generated and categorized into actionable risk levels

  ## What This Project Demonstrates

- Exploratory Data Analysis on user behavior data
- Feature engineering for behavioral prediction
- Binary classification with probabilistic outputs
- Model evaluation using precision–recall analysis
- Applied machine learning for recommendation systems



