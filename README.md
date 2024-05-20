# Sign Language Recognition Using Random Forest Classifier

## Project Overview

This project aims to develop a system for recognizing sign language gestures using machine learning techniques. The system is trained to identify 26 alphabets (A-Z) and 10 numbers (0-9) based on hand gestures. We have grouped the alphabets with dissimilar and similar hand gestures to improve recognition accuracy and efficiency.

## Features

- Recognition of 26 alphabets and 10 numbers.
- Grouping of alphabets with similar and dissimilar hand gestures for enhanced accuracy.
- Real-time gesture recognition.

## Dataset

- **Alphabets:** Images of individual alphabets (A-Z).
- **Numbers:** Images of individual numbers (0-9).
- **Grouped Alphabets:**
  - Group 1: Alphabets with dissimilar hand gestures (e.g., H, I, L).
  - Group 2: Alphabets with similar hand gestures (A, S, T).
  - Group 3: Alphabets with similar hand gestures (M, N, D).
  - Group 4: Alphabets and numbers with similar hand gestures (Z, K, 2, B, 4).

## Model Training

The model is trained using the RandomForest classifier. We employed the following steps:

1. **Data Preparation:** Preprocessing and annotation of the dataset.
2. **Model Training:** Leveraging the RandomForest classifier and pickle for model serialization. Extensive parameter tuning and experimentation were conducted to optimize performance.
3. **Model Evaluation:** Comprehensive evaluation tests using cross-validation to assess accuracy, precision, recall, and F1 score.
4. **Result Analysis:** In-depth analysis of the evaluation results to identify areas of improvement.

## Model Evaluation

The model was evaluated using several metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

These metrics provided insights into the model's performance and guided further refinements.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/IshitaChoudhuri/SignTech_MinorProject.git
