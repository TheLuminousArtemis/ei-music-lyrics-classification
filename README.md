## Data Collection and Preparation

### 1. Leveraging Popular Playlists:
- Playlists representing different moods (such as happy, sad, energetic, etc.) from Spotify were utilized.
- Songs from these playlists were extracted and saved into separate CSV files, categorizing them based on their mood.

### 2. Creating a Combined Dataset:
- These mood-specific CSV files were then merged to create a comprehensive dataset.
- The combined dataset included various features like song attributes, lyrics, artists, and genres, along with their associated moods.

### 3. Data Modification and Feature Extraction:
- The combined dataset was modified to create a training dataset.
- Unnecessary features like song names and track IDs were removed.
- Data preprocessing techniques, such as one-hot encoding and feature scaling, were applied to prepare the dataset for machine learning algorithms.

## Model Evaluation
### 1. Performance Metrics:
- Each classifier's performance was evaluated using metrics like accuracy, precision, recall, and F1 score.
- Accuracy represented the overall correctness of the model's predictions.
- Precision measured the proportion of true positive predictions out of all positive predictions.
- Recall calculated the proportion of true positive predictions out of all actual positives.
- F1 score provided a balance between precision and recall.

### 2. ROC Curve and AUC:
- Receiver Operating Characteristic (ROC) curves and Area Under the Curve (AUC) scores were utilized to assess the classifiers' ability to distinguish between different moods.

## Model Performance Summary
### 1. k-NN Classifier:
- Accuracy: 41.50%
- Precision: 42.61%
- Recall: 41.50%
- F1 Score: 41.45%

### 2. Hyperparameter Tuned k-NN Classifier:
- Accuracy: 98.15%
- Precision: 98.28%
- Recall: 98.15%
- F1 Score: 98.14%

### 3. Random Forest Classifier:
- Accuracy: 59.78%
- Precision: 59.62%
- Recall: 59.78%
- F1 Score: 59.03%

### 4. Hyperparameter Tuned Random Forest Classifier:
- Accuracy: 98.15%
- Precision: 98.16%
- Recall: 98.15%
- F1 Score: 98.15%

These scores highlight the accuracy and precision of each model, indicating their performance in classifying moods based on the given dataset.
