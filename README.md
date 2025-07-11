# CE880 Case Study: Analysis of Mental Well-being Factors

## Description
This project, developed as part of the CE880 Case Study, focuses on analyzing various factors related to mental well-being, specifically focusing on anxiety and related symptoms. The analysis is conducted using a Jupyter Notebook (`case_study.ipynb`) which performs data loading, preliminary data exploration, and generates visualizations to identify patterns and insights within the dataset.

## Table of Contents
1. Introduction
2. Dataset
3. Analysis and Visualizations
4. Key Findings
5. How to Run
6. Dependencies
7. Contact




## 1. Introduction
This project explores a dataset containing information about individuals' mental well-being, specifically focusing on symptoms related to anxiety, such as feeling sad or tearful, irritability, sleep disturbances, problems concentrating, overeating, feelings of guilt, problems bonding with a baby, and suicidal ideation. The primary goal is to understand the distribution of these symptoms across different age groups and identify any significant correlations or patterns. The analysis is performed using Python within a Jupyter Notebook environment, leveraging libraries like Pandas for data manipulation and Matplotlib/Seaborn for data visualization.




## 2. Dataset
The dataset used in this case study is a CSV file that contains various features related to mental well-being. The key columns include:
- `Age`: Age group of the individuals.
- `Feeling sad or Tearful`: Indicates if the individual feels sad or tearful (Yes/No).
- `Irritable towards baby & partner`: Indicates irritability towards baby and partner (Yes/No).
- `Trouble sleeping at night`: Indicates trouble sleeping (Yes/No).
- `Problems concentrating or making decision`: Indicates problems concentrating or making decisions (Yes/No).
- `Overeating or loss of appetite`: Indicates issues with appetite (Yes/No).
- `Feeling of guilt`: Indicates feelings of guilt (Yes/No).
- `Problems of bonding with baby`: Indicates problems bonding with baby (Yes/No).
- `Suicide attempt`: Indicates if there was a suicide attempt (Yes/No).
- `Feeling anxious`: Indicates if the individual feels anxious (Yes/No).

The dataset contains 1503 entries and 10 columns. Missing values are present in some columns, notably 'Irritable towards baby & partner', 'Problems concentrating or making decision', and 'Feeling of guilt'. These missing values are handled during the analysis.




## 3. Analysis and Visualizations
The Jupyter Notebook (`case_study.ipynb`) performs the following analysis steps:

### Data Loading and Initial Inspection
The dataset is loaded into a Pandas DataFrame. Initial inspection includes:
- Displaying the first few rows (`df.head()`).
- Checking column names (`df.columns`).
- Getting a summary of the DataFrame, including data types and non-null values (`df.info()`).
- Generating descriptive statistics for numerical columns (`df.describe()`).
- Checking the shape of the DataFrame (`df.shape`).
- Identifying and summing missing values for each column (`df.isnull().sum()`).

### Missing Value Handling
The notebook identifies columns with missing values and notes observations about them. While specific imputation methods are not explicitly shown in the preview, the analysis acknowledges their presence.

### Data Distribution Analysis
- **Age Group Distribution of Anxious Individuals**: A pie chart is generated to visualize the distribution of anxious individuals across different age groups. This helps in understanding which age groups are most affected by anxiety.
- **Feature Distributions**: Bar plots are generated for each categorical feature to show the count of 'Yes' and 'No' responses. This provides an overview of the prevalence of each symptom.
- **Two-Way Data Distributions**: Bar plots are also used to show the relationship between 'Age' and 'Feeling anxious', as well as other symptoms and 'Feeling anxious'. This helps in identifying potential correlations between age groups, specific symptoms, and anxiety.

### Key Observations from Visualizations:
- The age group 35-40 appears to have the highest number of anxious people.
- The age group 25-30 appears to have the least number of anxious people.
- Visualizations help in understanding the distribution of various mental well-being indicators across the dataset.




## 4. Key Findings
Based on the analysis performed in the `case_study.ipynb` notebook, the following key findings have been observed:
- **Age-related Anxiety**: The age group 35-40 shows the highest prevalence of anxiety, while the 25-30 age group exhibits the lowest. This suggests a potential age-related pattern in the occurrence of anxiety within the studied population.
- **Symptom Distribution**: The individual distributions of symptoms like 'Feeling sad or Tearful', 'Irritable towards baby & partner', 'Trouble sleeping at night', 'Problems concentrating or making decision', 'Overeating or loss of appetite', 'Feeling of guilt', 'Problems of bonding with baby', and 'Suicide attempt' provide a clear picture of their overall prevalence in the dataset.
- **Correlation with Anxiety**: The two-way data distributions highlight how each symptom correlates with 'Feeling anxious'. This can help in identifying which specific symptoms are more frequently associated with anxiety.




## 5. How to Run
To run this project and reproduce the analysis, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/sherrywilly/CE880_Case_Study.git
    cd CE880_Case_Study
    ```

2.  **Install dependencies**:
    Ensure you have Python installed. It is recommended to use a virtual environment.
    ```bash
    pip install pandas matplotlib seaborn
    ```

3.  **Open the Jupyter Notebook**:
    ```bash
    jupyter notebook case_study.ipynb
    ```

4.  **Run the cells**: Once the notebook is open in your browser, you can run all cells sequentially to execute the data analysis and generate the visualizations.




## 6. Dependencies
This project requires the following Python libraries:
- `pandas`
- `matplotlib`
- `seaborn`

These can be installed using `pip` as shown in the "How to Run" section.




## 7. Contact
For any questions or inquiries, please contact [sherrywilly](https://github.com/sherrywilly).


