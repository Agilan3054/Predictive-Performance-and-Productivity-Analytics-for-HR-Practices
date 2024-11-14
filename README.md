# PerformAI - Employee Performance Analytics Using Generative AI

PerformAI is an AI-driven solution designed to help HR teams identify high performers and analyze factors contributing to success within an organization. The project uses state-of-the-art machine learning models, including **CatBoost**, **SHAP** for model interpretability, and **OpenAI GPT-3** and **T5** for personalized feedback and goal generation. 

## Features

- **High Performer Prediction**: Predicts whether an employee is a high performer based on various performance metrics such as KPI score, task completion, leadership score, etc.
- **Model Interpretability**: Uses **SHAP** to explain the contributions of each feature to the prediction.
- **Personalized Feedback Generation**: Generates personalized feedback for employees using **OpenAI GPT-3** based on their performance data.
- **Performance Goal Generation**: Uses the **T5 model** to generate dynamic performance goals for employees based on their metrics.
- **Streamlit Dashboard**: Provides an interactive user interface to visualize predictions, SHAP plots, and feedback in a web-based dashboard.

## Requirements

- Python 3.x
- `pandas` - for data manipulation
- `numpy` - for numerical operations
- `catboost` - for training the predictive model
- `shap` - for model explanation and interpretability
- `openai` - for GPT-3 integration
- `transformers` - for T5 model
- `streamlit` - for creating the interactive web dashboard
- `scikit-learn` - for preprocessing and splitting data
