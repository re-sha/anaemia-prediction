# Anaemia Detection Using Decision Tree Classifier


## Project Overview
This project aims to predict anaemia in individuals based on various features using a Decision Tree Classifier. The dataset used for this project contains information about patients, including their sex and various pixel measurements. The model is trained to classify whether an individual is anaemic or not.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation
To run this project, you need to have Python installed along with the following libraries:

- pandas
- scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas scikit-learn
```

## Usage
1. Clone this repository or download the project files.
2. Place the `anaemia_dataset.csv` file in the project directory.
3. Run the script using Python:

```bash
python anaemia_detection.py
```

## Data Description
The dataset `anaemia_dataset.csv` contains the following columns:

- **Number**: Unique identifier for each patient (not used in the model).
- **Sex**: Gender of the patient (M/F).
- **%Red Pixel**: Percentage of red pixels in the image.
- **%Green Pixel**: Percentage of green pixels in the image.
- **%Blue Pixel**: Percentage of blue pixels in the image.
- **Hb**: Hemoglobin level of the patient.
- **Anaemic**: Target variable indicating whether the patient is anaemic (1) or not (0).

## Model Training
The project uses a Decision Tree Classifier to predict anaemia. The following steps are performed:

1. **Data Preprocessing**:
   - Load the dataset using pandas.
   - Encode the categorical variable 'Sex' using `LabelEncoder`.
   - Split the dataset into features (`X`) and target variable (`y`).

2. **Train-Test Split**:
   - The dataset is divided into training and testing sets using `train_test_split`.

3. **Model Fitting**:
   - A Decision Tree Classifier is instantiated and fitted to the training data.

4. **Predictions**:
   - The model is used to predict outcomes on the test set.

## Results
The accuracy of the model is evaluated using the accuracy score metric. The output will display the accuracy of the predictions made on the test dataset.

```python
print('Accuracy of dataset is: ')
score
```

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to modify any section to better fit your project's specifics or your personal style! 
