Genre Movie Prediction)
This repository contains a project focused on predicting the genres of TV shows and movies through a multi-label classification task. The project is divided into two main 
sections: Data Analytics and Data Science.

Project Overview)
The objective of this project is to develop a machine learning model that can accurately predict the genres of TV shows and movies. The project was approached in two stages:

    Data Analytics: This stage involved exploring the dataset to gain insights into the data through various visualization tools.
    Data Science: In this stage, a predictive model was developed to classify genres based on features derived from the dataset.

Data Analytics)
In the Data Analytics section, the goal was to understand the dataset and extract meaningful insights using visualization techniques. Various charts and plots were created to 
identify patterns and trends within the data.

Data Science)
The Data Science section focused on building a model capable of predicting the genre of TV shows and movies. This process included several key steps:

Preprocessing)

    Textual Preprocessing: Since some features were textual, they required cleaning and vectorization. The TF-IDF (Term Frequency-Inverse Document Frequency) method was 
    employed for vectorizing the text data.

    Categorical Encoding: A categorical feature was encoded using the LeaveOneOutEncoder, which helps in handling high-cardinality categorical variables. Another categorical
    column was encoded through one-hot_encoding.

    Missing Value Imputation: Missing values in the dataset were treated through appropriate imputation techniques to ensure the completeness of the feature matrix.

    Class Imbalance Handling: The dataset exhibited class imbalance, which was addressed using cost-sensitive learning techniques to ensure that the model did not favor the 
    majority classes.

Modeling)

    Algorithm Used: The project focused on a single algorithm, Logistic Regression, for the multi-label classification task. Logistic Regression was chosen for its simplicity 
    and effectiveness, and it was adapted for the multi-label scenario.

Evaluation)

    Model Performance: The model's performance was thoroughly evaluated using appropriate metrics for multi-label classification. This assessment helped in understanding the 
    strengths and weaknesses of the model and provided insights for potential improvements.

Technologies Used)

    Python
    Pandas
    Scikit-learn
    Matplotlib
    Seaborn
    TF-IDF Vectorization
    LeaveOneOutEncoder

Contact)
For questions or further information, please contact [Anahita Zahedi Nameghi] at [AnahitaZahediNameghi@gmail.com].
