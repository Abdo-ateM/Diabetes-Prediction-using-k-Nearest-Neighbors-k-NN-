# Diabetes Classification using K-Nearest Neighbors (K-NN)

This project aims to classify diabetes patients using the K-Nearest Neighbors (K-NN) algorithm. It involves two primary components:

## Project Overview

### Standard K-NN Implementation
- Utilizes `scikit-learn` to implement the K-NN algorithm.
- The dataset (`diabetes.csv`) includes various health metrics such as:
  - Pregnancies
  - Glucose level
  - Blood pressure
  - Skin thickness
  - Insulin
  - BMI
  - Pedigree
  - Age
  - Outcome (1 for diabetic, 0 for non-diabetic)
- Data preprocessing steps include handling missing values.
- The model is trained, and its performance is evaluated using metrics like accuracy, confusion matrix, and cross-validation.

### Custom K-NN Implementation from Scratch
- Implements the K-NN algorithm from scratch using `numpy`.
- Similar preprocessing steps as the standard implementation.
- Custom logic to calculate distances, find nearest neighbors, and classify the data points.

## Files in the Repository

- `diabetes.csv`: The dataset containing health metrics for diabetes classification.
- `K_NN.ipynb`: Jupyter notebook implementing the K-NN algorithm using `scikit-learn`.
- `K_NN_scratch.ipynb`: Jupyter notebook implementing the K-NN algorithm from scratch.

## Getting Started

To get started with this project, clone the repository and install the necessary dependencies.

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/diabetes-classification-knn.git
    cd diabetes-classification-knn
    ```

2. Install the required libraries:
    ```sh
    pip install numpy pandas scikit-learn matplotlib seaborn
    ```

3. Open the Jupyter notebooks:
    ```sh
    jupyter notebook
    ```

## Usage

1. Open and run the `K_NN.ipynb` notebook to see the implementation using `scikit-learn`.
2. Open and run the `K_NN_scratch.ipynb` notebook to see the custom implementation from scratch.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
