# Data Cleaning and Wrangling with Python

This repository contains the code and documentation for cleaning and wrangling data using Python. The purpose of this project is to demonstrate the steps involved in preprocessing and transforming raw data to make it suitable for analysis or further processing.


## Data Source

The raw data used in this project is sourced from a youtube channel mentioned in references section. It includes a dataset with the following characteristics:

- Size: 76378 rows
- Format: Comma-separated values (CSV)
- Columns: 9

        The dataset is structured as follows:

        first name: Person, last name: Human, date: end of time
        ,,,,,,,,,,
        Row Type, Iter Number, Power1, Speed1, Speed2, Electricity, Effort, Weight, Torque,
        Iter, 1, 360, 108, 863, 599, 680, 442, 982,
        Iter, 2, 684, 508, 613, 241, 249, 758, 639,
        Iter, 3, 365, 126, 825, 407, 855, 164, 86,
        Iter, 4, 764, 594, 304, 718, 278, 674, 774,
        Iter, 5, 487, 97, 593, 206, 779, 800, 123,
        Average, 182, 361, 741, 231, 731, 493, 847, 237,
        Maximum, 276, 33, 97, 154, 25, 922, 9, 312,
        Std.Dev., 523, 1000, 34, 904, 237, 600, 170, 553,
        Total, 336, - , - , - , - , 977, 744, 652,
        ,,,,,,,,,,

    
This format consists of 9 columns representing various attributes. Each row corresponds to a specific iteration, with data provided for the respective attributes.



## Task


![task file](reports/figures/task.png)




## Data Cleaning Process

The data cleaning and wrangling process involved the following steps:

1. **Data Inspection**: Initially, we inspected the raw data to gain a better understanding of its structure, missing values, and inconsistencies.

2. **Handling Missing Values**: We identified missing values in the dataset and applied appropriate techniques to handle them. This involved methods such as imputation, deletion, or interpolation.

3. **Data Transformation**: Various transformations were performed on the data to ensure its quality and suitability for analysis. This included tasks such as data type conversions, scaling, normalization, or standardization.

4. **Removing Duplicates**: We identified and removed any duplicate records present in the dataset to ensure data integrity.

5. **Dealing with Outliers**: Outliers were identified and treated using methods such as winsorization, capping, or removal based on domain knowledge and statistical analysis.

6. **Feature Engineering**: New features were derived from the existing data or external sources to enhance the predictive power of the dataset. This involved techniques such as creating interaction terms, binning, or one-hot encoding categorical variables.

7. **Data Validation**: Finally, we performed data validation checks to ensure the quality and consistency of the cleaned dataset. This involved verifying constraints, ranges, and logical relationships within the data.

## Code Examples

The code examples provided in this repository demonstrate how to perform the aforementioned data cleaning and wrangling tasks using Python. The examples are organized into separate scripts or Jupyter notebooks for better modularity and readability.

## Dependencies

To run the code in this repository, the following Python libraries are required:

- pandas
  
Please refer to the `requirements.txt` file for detailed version information and installation instructions.

## Usage

You can clone this repository and explore the code examples provided. Each script or notebook is self-contained and includes comments to guide you through the data cleaning and wrangling process.

Feel free to adapt and modify the code to suit your own datasets and requirements. If you encounter any issues or have questions, please open an issue on GitHub.

## References

I'm grateful to Shashank Kalanithi for providing me with invaluable knowledge and guidance, which has greatly enhanced my skills and added significant value to my work.

link : https://www.youtube.com/watch?v=sSnbmbRmtSA&t=142s


## License

This project is licensed under the [MIT License](LICENSE).
