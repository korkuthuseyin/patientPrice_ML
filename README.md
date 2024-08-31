# Grade Estimation Project

This project applies machine learning algorithms to estimate student grades based on various features such as travel time, study time, gender, internet access, free time, family support, and more. The implementation is done in a Jupyter Notebook (`gradeEstimation.ipynb`) using data from the `student-mat.csv` file.

## Project Overview

The goal of this project is to predict student grades using a dataset containing students' personal and academic information. Key features include:

- **Travel Time**: Time taken by the student to travel from home to school.
- **Study Time**: Weekly study hours.
- **Gender**: Student's gender.
- **Internet Access**: Availability of internet access at home.
- **Free Time**: Free time available after school.
- **Family Support**: Level of support from family.

The workflow includes data preprocessing, visualization, and model training to make accurate grade predictions.

## Files in the Repository

- **`gradeEstimation.ipynb`**: Jupyter Notebook containing the project workflow, from data loading to model prediction.
- **`student-mat.csv`**: Dataset file with student information used for training and testing the models.

## Dependencies

The project requires the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

Install the dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
