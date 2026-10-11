# AI/ML Internship Task – Data Cleaning Using Python and Pandas

## Project Overview

This project was completed as part of the Veda Technology AI/ML internship task. It demonstrates basic data-cleaning techniques using Python and Pandas on the Titanic dataset.

## Objective

To inspect and clean a real-world dataset by handling missing values, removing duplicate records, and correcting data types.

## Tools Used

- Python
- Pandas
- Jupyter Notebook

## Dataset

The Titanic dataset contains passenger information such as age, fare, passenger class, sex, embarkation details, and survival status.

## Cleaning Steps

1. Loaded and inspected the original dataset.
2. Examined missing values and duplicate records.
3. Saved a copy of the original dataset.
4. Filled missing numerical values in `age` and `fare` using their median values.
5. Filled missing categorical values in `embarked` and `embark_town` using their mode values.
6. Removed the `deck` column because it contains a high proportion of missing values.
7. Removed duplicate records.
8. Converted appropriate columns to numerical and categorical data types.
9. Saved the cleaned dataset as a CSV file.
10. Verified the final dataset.

## Project Files

- `titanic_original.csv` – Original dataset.
- `titanic_cleaned.csv` – Cleaned dataset.
- `data_cleaning.ipynb` – Jupyter Notebook containing the code and results.

## Results

The cleaning workflow produces an exported cleaned dataset and a notebook documenting the operations. The notebook displays the original and final shapes, missing-value counts, duplicate counts, and data types for verification.

## Conclusion

This project demonstrates how Pandas can be used to improve dataset quality through missing-value handling, duplicate removal, and data-type correction. These steps help prepare data for exploratory data analysis and subsequent machine-learning workflows.

## Author

Archita Pujari

AI/ML Internship – Veda Technology
