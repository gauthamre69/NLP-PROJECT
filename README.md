# NLP-PROJECT
Mental Health Prediction using NLP

## Overview
This project predicts mental health conditions using machine learning models based on text data. The dataset contains mental health-related topics and text descriptions.

## Files
1. **`Mental_Health_Prediction.ipynb`**:  
   A Jupyter Notebook for data analysis, preprocessing, and model training.
2. **`dataset.csv`**:  
   The dataset with the following columns:
   - **`health`**: The category of the mental health topic (e.g., PTSD, relationships).  
   - **`text`**: Text data related to mental health topics.  
   - **`label`**: Binary label (1 for mental health-related text, 0 otherwise).

## Requirements
Install the necessary Python libraries using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Use
1. Place the `Mental_Health_Prediction.ipynb` and `dataset.csv` files in the same directory.
2. Open the notebook in Jupyter and run the cells sequentially to replicate the analysis.

## Dataset Details
- **Rows**: 2838  
- **Columns**: 3  
- **No Missing Values**.  
- **Target**: The `label` column indicates whether the text is related to mental health issues.

### Example Data
| health           | text                                              | label |
|-------------------|---------------------------------------------------|-------|
| ptsd             | He said he had not felt that way before...        | 1     |
| assistance       | Hey there r/assistance, Not sure if this is...    | 0     |

## Results
The project provides insights and predictions on mental health text data using machine learning techniques.

