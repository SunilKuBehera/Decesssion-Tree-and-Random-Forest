# Heart Disease Prediction | by using Decision Trees and Random Forest Classifier

This repository demonstrates the use of Decision Tree and Random Forest classifiers to predict the presence of heart disease using a dataset of patient medical attributes.

## Dataset

The dataset, `HeartDisease.csv`, contains 1,025 records and 14 columns, each representing a different medical feature or the prediction target. The columns are:

- **age**: Age of the patient (years)
- **sex**: Sex (1 = male, 0 = female)
- **cp**: Chest pain type (0–3)
- **trestbps**: Resting blood pressure (mm Hg)
- **chol**: Serum cholesterol (mg/dl)
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results (0–2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise-induced angina (1 = yes, 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment (0–2)
- **ca**: Number of major vessels colored by fluoroscopy (0–4)
- **thal**: Thalassemia (0 = normal, 1 = fixed defect, 2 = reversible defect, 3 = unknown)
- **target**: Presence of heart disease (1 = disease, 0 = no disease)

There are **no missing values** in the dataset.

### Data Statistics

- **Mean Age**: ~54 years (Range: 29–77)
- **Mean Serum Cholesterol**: ~246 mg/dl (Range: 126–564)
- **Target Distribution**: Approximately balanced between presence (1) and absence (0) of heart disease.

## Workflow

The main analysis is in the notebook **5.Decision Trees and Random Forests.ipynb**:

1. **Data Loading**: Reads the CSV file into a pandas DataFrame.
2. **Exploratory Data Analysis**: Checks for missing values and analyzes basic statistics.
3. **Feature Selection**: Splits the data into features (X) and target (y).
4. **Train-Test Split**: Uses 80% of data for training and 20% for testing.
5. **Modeling**:
    - Decision Tree Classifier
    - Random Forest Classifier
6. **Model Performance Report**: checked accuracy score and classification reports.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## License

This project is licensed under the [Apache 2.0 License](LICENSE).
