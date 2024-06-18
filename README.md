# Orthogonal Procrustes Analysis with Data Visualization

This repository contains a Python implementation of the orthogonal Procrustes problem applied to the Iris dataset, with added noise and data visualization.

## Overview

The orthogonal Procrustes problem involves finding the best orthogonal matrix that aligns one dataset with another. This project demonstrates the application of this technique on the Iris dataset and visualizes the transformation.

## Features

- **Data Loading**: Load the Iris dataset using `scikit-learn`.
- **Dimensionality Reduction**: Apply PCA to reduce the dataset to 2 dimensions for visualization.
- **Noise Addition**: Add noise to one subset of the dataset to demonstrate the transformation.
- **Orthogonal Procrustes Analysis**: Implement the orthogonal Procrustes solution using SVD.
- **Data Visualization**: Visualize the original, noisy, and transformed datasets, along with the decision boundary.

## Requirements

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/pratirath06/Orthogonal-Procrustes.git
    ```

2. **Navigate to the Directory**:
    ```bash
    cd Orthogonal-Procrustes
    ```

3. **Install Dependencies**:
    Install the required Python libraries using `pip`:
    ```bash
    pip install numpy pandas matplotlib seaborn scikit-learn
    ```

4. **Run the Script**:
    Execute the Python script to perform orthogonal Procrustes analysis and visualize the results:
    ```bash
    python Orthogonal Procrustes.ipynb
    ```

## Visualization

The script generates plots that visualize the original, noisy, and transformed datasets, as well as the decision boundary that separates the transformed datasets.

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request with improvements or new features.

## Acknowledgements

This project uses the Iris dataset, available from the UCI Machine Learning Repository.

Special thanks to all the open-source communities for their resources.

Happy coding and good luck with your projects!

Brought by, Pratirath Gupta.

