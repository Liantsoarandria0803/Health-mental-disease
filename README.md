# Depression Analysis and Prediction

This repository contains a Jupyter Notebook that analyzes a dataset related to depression and builds a predictive model to classify individuals as depressed or not based on various features.

## Dataset

The dataset used in this analysis is `depression.csv`. It contains several features that are used to predict the target variable `depressed`. The features include:

- `age`: Age of the individual
- `gender`: Gender of the individual
- `education`: Education level
- `marital_status`: Marital status
- `employment_status`: Employment status
- `income`: Income level
- `family_history`: Family history of mental illness
- `physical_activity`: Level of physical activity
- `sleep_hours`: Average sleep hours per night
- `stress_level`: Self-reported stress level

The target variable is:

- `depressed`: Indicates whether the individual is depressed (1) or not (0)

## Notebook Overview

The notebook is structured as follows:

1. **Data Loading and Exploration**: The dataset is loaded, and initial exploratory data analysis (EDA) is performed to understand the distribution of features and the target variable.

2. **Data Preprocessing**: Steps include handling missing values, encoding categorical variables, and scaling numerical features to prepare the data for modeling.

3. **Model Building**: A logistic regression model is trained to predict the likelihood of depression based on the input features.

4. **Model Evaluation**: The performance of the model is evaluated using metrics such as accuracy, precision, recall, and the ROC-AUC score.

5. **Conclusion**: Insights from the analysis and model performance are summarized.

## Requirements

To run the notebook, ensure you have the following Python libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install these packages using `pip`:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Liantsoarandria0803/Health-mental-disease.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Health-mental-disease
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Depression.ipynb
   ```

4. Run the cells sequentially to perform the analysis and view the results.

## Results
Best model : catBoost with F1 score : 0.9621830111721936
## Contributing

Contributions are welcome! If you have suggestions for improvements or additional analyses, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

