## **Parkinson’s Disease Diagnosis Based on Speech Signals Dataset Using Machine Learning**

## Project Overview
This project focused on leveraging machine learning techniques to diagnose Parkinson's disease based on speech signals dataset. The multi-step process, from data **preprocessing** and **dimensionality reduction** to **model evaluation**, contributes to the development of accurate and robust diagnostic tools in healthcare.

### Skills Learned:
- Data preprocessing and cleaning.
- Handling imbalanced datasets.
- Model training, testing, and evaluation.
- Feature engineering and dataset splitting.
- Machine learning classification algorithms.
- Performance evaluation with accuracy metrics.

### Tools & Libraries:
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- imbalanced-learn
- Python
- Google Colab
- Google Drive

## Dataset
### Dataset Overview:

The data used in this study were gathered from 188 patients with PD (107 men and 81 women) with ages ranging from 33 to 87 at the Department of Neurology in Cerrahpaşa Faculty of Medicine, Istanbul University. The control group consists of 64 healthy individuals (23 men and 41 women) with ages varying between 41 and 82. During the data collection process, the microphone is set to 44.1 KHz and following the physician's examination, the sustained phonation of the vowel /a/ was collected from each subject with three repetitions.

### Attribute Information:

Various speech signal processing algorithms including Time Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform based Features, Vocal Fold Features and TWQT features have been applied to the speech recordings of Parkinson's Disease (PD) patients to extract clinically useful information for PD assessment.

### Data Set Citation:

Sakar, C.O., Serbes, G., Gunduz, A., Tunc, H.C., Nizam, H., Sakar, B.E., Tutuncu, M., Aydin, T., Isenkul, M.E. and Apaydin, H., 2018. A comparative analysis of speech signal processing algorithms for Parkinson's disease classification and the use of the tunable Q-factor wavelet transform. Applied Soft Computing, DOI: https://doi.org/10.1016/j.asoc.2018.10.022

## Steps
### 1. Import Required Libraries:
- The code begins by importing essential libraries such as Scikit-learn, Numpy, Pandas, and Matplotlib.

### 2. Load and explore Dataset: 
- The dataset is loaded from Google Drive using the Pandas library, specifically reading a CSV file (pd_speech_features.csv).
- The dataset is explored using methods like head() to view the first few rows, and describe() for statistical summaries.

### 3. Data Preprocessing:

- Rename the target column.
- Handle imbalanced datasets using the imbalanced-learn library to ensure balanced training.
- Splitting the data into training and testing sets.

### 4. Train and Evaluate Model: 
- Machine learning models are trained on the preprocessed data, and the model performance is evaluated using metrics such as accuracy score.

### 5. Visualization: 
- Use Matplotlib to visualize insights from the dataset or model performance.

## Future Work:
- Experiment with different machine learning models and hyperparameters to improve accuracy.
- Implement cross-validation to better assess model performance.
- Explore other evaluation metrics, especially for imbalanced datasets (e.g., F1-score, precision, recall).
