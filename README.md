# CS205 AI Project [UCR] - Subject to copywrite

This repository contains the code for the CS236 AI project, which focuses on feature selection algorithms. The project is part of the CS236 course at University Of California, Riverside

## Team Members
- Akash Bilgi
- Amrutha Alewoor

## Description
The goal of this project is to implement and evaluate feature selection algorithms for machine learning tasks. The code includes two main algorithms: Forward Selection and Backward Elimination. These algorithms aim to identify the most informative subset of features from a given dataset.

## Dataset
The project utilizes various datasets for feature selection. The available dataset choices are:
1. CS170_small_Data__27.txt
2. CS170_large_Data__1.txt
3. CS170_XXXlarge_Data__17.txt
4. Real_world_data(Wisconsin Breast Cancer Dataset).csv

## Usage
To run the feature selection on a dataset, use the `run()` function. The function provides both interactive and argument-based options:

### Options
- [no arguments]: Run the function without arguments to interactively select the dataset and algorithm.
- [arg1, arg2]: Provide the `dataset_choice` and `algorithm_choice` as arguments to run the function with specific choices.

### Examples

1. Run the function interactively:
```python
run()  # Perform feature selection on a dataset interactively.
```

2. Provide the `dataset_choice` and `algorithm_choice` as arguments:
```python
dataset_choice = 2  # Select the second dataset
algorithm_choice = 1  # Perform Forward Selection algorithm

run(dataset_choice, algorithm_choice)  # Run the function with specific choices
```

## Dependencies
- Python 3.x
- NumPy
- Pandas (for dataset 4: Real_world_data(Wisconsin Breast Cancer Dataset).csv)

## License
[MIT License, Apache License 2.0, UCR]

Feel free to explore the code and experiment with different datasets and algorithm choices.

Happy feature selection!
```
