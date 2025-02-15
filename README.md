# Text Classification with Scikit-Learn 📚🤖

This project demonstrates **text classification** using **Scikit-Learn** on the **IMDb movie review dataset**. The goal is to classify movie reviews as positive or negative using a logistic regression model. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **Scikit-Learn** to build and train a logistic regression model for text classification. 🤖📚
- Leverages the **IMDb movie review dataset** for training and validation. 🧠🔍
- Implements text preprocessing, model training, and evaluation. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install scikit-learn
```

---

## Usage 🖥️

1. **Load Dataset**: The script downloads and loads the IMDb movie review dataset.
2. **Preprocess Data**: Applies text preprocessing and splits the data into training and test sets.
3. **Build Model**: Defines and trains a logistic regression model.
4. **Evaluate Model**: Evaluates the model's performance using cross-validation and grid search.
5. **Test Model**: Evaluates the model's performance on the test set.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and preprocesses the IMDb movie review dataset.
  - Applies text preprocessing and splits the data into training and test sets.

- **Model Definition**:
  - Defines a logistic regression model for text classification.
  - Uses cross-validation and grid search for hyperparameter tuning.

- **Training**:
  - Trains the model using the training set.
  - Tracks cross-validation accuracy.

- **Evaluation**:
  - Evaluates the model's performance on the test set.
  - Prints the test accuracy.

---

## Results 📊

- **Cross-Validation Accuracy**: The model achieves high cross-validation accuracy.
- **Test Accuracy**: Evaluates the model's performance on the test set.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Mean cross-validation accuracy: 0.88
Best cross-validation score: 0.89
Best parameters: {'C': 1}
Test score: 0.88
```

---

## Dependencies 📦

- `scikit-learn`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
