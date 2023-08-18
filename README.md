# Iris_Flower_Classification_Using_KNearest_Neighbours

## Introduction

The Iris flower classification project uses the Iris dataset to demonstrate a simple machine-learning workflow. It covers data loading, exploration, preprocessing, model building, evaluation, and data visualization.

## Prerequisites

- Python (>= 3.6)
- Required Python packages can be installed using: `pip install -r requirements.txt`

## Installation

1. Clone this repository: `git clone https://github.com/abhiverse01/iris-flower-classification_using_knearest_neighbours.git`
2. Navigate to the project directory: `cd iris-flower-classification-using-knearest-neighbours`

## Usage

1. Install the required packages as mentioned in the Prerequisites section.
2. Run the `iris_classification.py` script: `python iris_classification.py`
3. Follow the on-screen instructions to see the classification results and visualizations.

## Data Exploration

The Iris dataset consists of four features: sepal length, sepal width, petal length, and petal width. The target variable is the species of the Iris flower.

## Data Preprocessing

The dataset is split into training and testing sets. Features are standardized using the `StandardScaler`.

## Model Building

The K-Nearest Neighbors (KNN) algorithm is used for classification. The model is trained using the training data.

## Evaluation

The model's accuracy is calculated on the test data. The classification report provides additional performance metrics.

## Visualization

Data visualizations are included to provide insights into the dataset and model performance:
- Pair plot to visualize feature relationships
- Box plots to show feature distributions for different species
- Correlation heatmap to display feature correlations

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
