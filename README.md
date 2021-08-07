## crypto-veeran
### Malicious Website blockers using ML

For further Data Pre-Processing, I have removed irrelevant fields to make my data collection more concise.
The reformed dataset contains 450,160 Rows & 3 Columns.
### Labels :
URL – Combination of Benign and Malicious URLs
LABEL – Two Classification – [Benign & Malicious]
RESULT – Boolean; Benign (0), Malicious (1)

With the Column “URL” as input for the malicious URL detection model.
The dataset is labeled, so any supervised learning algorithms can be used for classification and analysis.
There are two separate data collection for training and testing
Training dataset : 135048 rows 
Testing dataset : 315112 rows

## Model built by using Python
### Libraries used:
1. Numpy – for n-dimensional array and numerical operations
2. Pandas – Data manipulations and Data Analysis
3. Seaborn, Matplotlib – plotting graphs and data visualization
4. Scikit-learn – In-built machine learning algorithms

The dataset is stored in csv file (comma separated values)
Dataset is imported for training, testing and analysis. From the result, graphs are plotted and all 3 algorithms are synchronously compared based on accuracy and performance during training and testing on the dataset.

