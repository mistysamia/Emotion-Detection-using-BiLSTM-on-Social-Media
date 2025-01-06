# Emotion Detection using BiLSTM on Social Media

## Dataset 
   Download dataset (text.csv) from : [Emotions](https://www.kaggle.com/datasets/nelgiriyewithana/emotions)
## Python Version and Third-Party Libraries

### Python Version:
    Python Version: 3.10.12

### Third-Party Libraries:
    1. Pandas: 2.2.2
    2. NumPy: 1.26.4
    3. Seaborn: 0.13.2
    4. Matplotlib: 3.8.0
    5. TensorFlow: 2.17.1
    6. NLTK (Natural Language Toolkit): 3.9.1
    7. scikit-learn: 1.6.0
    8. SpaCy: 3.7.5
    9. Gensim: 4.3.3

## Running the Code

Follow the steps below to run the code in the correct order:
### 1. **Install Python and Third-Party Libraries**
Before running the code, ensure that **Python 3.10.12** is installed. If necessary, update to this version.

Install the required libraries by running the following command in your terminal:

```pip install pandas==2.2.2 numpy==1.26.4 seaborn==0.13.2 matplotlib==3.8.0 tensorflow==2.17.1 nltk==3.9.1 scikit-learn==1.6.0 spacy==3.7.5 gensim==4.3.3```

### 2. **Pre_Processing.ipynb**  
- **In the Data Load section:**  
  Add the path to the dataset file (`text.csv`).

- **In the Export Dataset section:**  
  Specify the path where the preprocessed dataset will be stored (e.g., `preprocessed_dataset.csv`).

- Run the file Pre_Processing.ipynb.
---

### 3. **Feature_Analysis.ipynb**  
- **In the Data Load section:**  
  Add the path to the preprocessed dataset (`preprocessed_dataset.csv`).
  
- Run the file Feature_Analysis.ipynb.
---

### 4. **BiLSTM_Model.ipynb**  

- **In the Data Load section:**  
  Add the path to the preprocessed dataset (`preprocessed_dataset.csv`).

- Run the file BiLSTM_Model.ipynb.
---

After following the above steps, the code should run successfully and the output should be displayed seamlessly.

