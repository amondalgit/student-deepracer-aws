# Five steps of Machine Learning
    define the problem -> build the dataset -> train the model-> evaluate the model -> use the model

## 1. Define the Problem
>### ML tasks (most common)
>1. Supervised Learning (uses label)
>    1. Classification (if solution labels are categotical variable)
>    2. Regression (if solution labels are continuous variable)
>2. Unsupervised Learning (uses unlabelled data)
>    1. Clustering (find any naturally occuring group in the data)

## 2. Build the Dataset
>**Data Collection**: collect data related to your defined problem
>   * SQL queries
>   * custom webscraper applications
>
>**Data Inspection**: 
>   * finding outliers
>   * replace/omit mission/incomplete data
>   * transform collected data to desired format to be used by model (like categorical to numerial)
>
>**Summary Stat**:
>   * Trend in the data (pdf, cdf)
>   * scale of the data (measure of variability)
>   * shape of the data (central tendency, distribution)
>
>**Data Visualization**:
>   communicate the findings to project stakeholders

## 3. Model Training
>**Splitting Dataset**:
>   * there will be two factions.
>       1. Training dataset (holds majority of datapoints ~80%)
>       2. Testing dataset (model has not seen these before while training)
>### Key Terms
>   * **Model parameters**: settings that the training algorithms can update to change hoe thw model behaves. (general used terms are Weights & Biases)
>   * **Loss functions**: defining model's distance from the actual results
>   * **Hyperparameters**: settings on the model that are not changed during training, but can affect how quickly or how reliably the model trains (e.g. the number of clusters the model should identify)
#### Key terms from this lesson:
* **Impute** is a common term referring to different statistical tools that can be used to calculate missing values from your dataset.
* **Outliers** are data points that are significantly different from other date in the same sample.