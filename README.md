
# Gaussian Mixture Model (GMM) Clustering on Iris Dataset

## Overview
This project demonstrates clustering using the **Expectation-Maximization (EM)** algorithm implemented via **Gaussian Mixture Model (GMM)** from the `sklearn.mixture` module. The clustering is performed on the **Iris dataset**, which consists of numerical features representing flower characteristics.

## Dataset
The dataset used is the **Iris dataset**, which contains the following features:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`

Ensure the dataset (`IRIS.csv`) is available in the same directory as the script.

## Installation & Requirements
To run this project, ensure you have the following dependencies installed:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Run the script**:
   ```bash
   python gmm_clustering.py
   ```

## How It Works
1. The script loads the dataset using **Pandas**.
2. It extracts numerical features relevant for clustering.
3. It determines the optimal number of clusters using **Bayesian Information Criterion (BIC)**.
4. A **Gaussian Mixture Model (GMM)** is trained on the dataset.
5. The data points are assigned cluster labels based on the trained model.
6. The results, including the identified clusters, are visualized using **Matplotlib**.

## Output
- **Optimal number of clusters** (based on BIC) is printed.
- A scatter plot visualizing the clustered data (first two features used for plotting).
- The dataset is updated with a new column indicating cluster labels.

## Example Visualization
The output visualization represents clustered data based on `sepal_length` and `sepal_width`:

![GMM Clustering Visualization](example_plot.png)

## License
This project is licensed under the MIT License.

## Author
Lukka Harshitha -  [GitHub Profile(https://github.com/Harshitha14-05)]

