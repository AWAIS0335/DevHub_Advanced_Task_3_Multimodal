# Task 3: Multimodal House Pricing

### Objective
To build a multimodal AI model that predicts house prices using both numerical data (e.g., bedrooms, area) and textual descriptions.

### Methodology
* **Text Processing:** Used TF-IDF Vectorizer to convert text descriptions into numerical feature vectors.
* **Numerical Processing:** Standardized numerical features using StandardScaler.
* **Model:** Concatenated both feature sets and trained a Random Forest Regressor for final prediction.

### Key Results
* Successfully combined textual and tabular data for regression.
* The multimodal approach accurately predicts prices based on unified inputs.
