# Cryptocurrency Clustering using K-Means and PCA

This repository contains a Python script that demonstrates how to cluster cryptocurrencies using K-Means clustering and Principal Component Analysis (PCA). The code reads cryptocurrency market data from a CSV file, preprocesses the data, performs clustering using K-Means, and visualizes the results. It also compares the clustering results using the original data and data reduced with PCA.

## Table of Contents

- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this code, you will need Python installed on your system. The code uses various libraries, such as pandas, hvplot, scikit-learn, and numpy, so you will also need to install these dependencies.

## Dependencies

The code relies on the following Python libraries:

- pandas
- hvplot
- scikit-learn
- numpy
- matplotlib

## Installation

To install the required dependencies, you can use the following pip command:

pip install pandas hvplot scikit-learn numpy matplotlib


## Usage

1. Clone this repository to your local machine.

2. Ensure you have the required dependencies installed as mentioned in the Dependencies section.

3. Place the CSV file containing cryptocurrency market data in the following directory:

/cryptocurrency_clustering/Resources/crypto_market_data.csv


4. Open the Python script `cryptocurrency_clustering.py` in your preferred Python editor or IDE.

5. Execute the script to perform the following steps:

    - Load the cryptocurrency market data from the CSV file.
    - Preprocess the data by scaling it using StandardScaler.
    - Identify the optimal number of clusters (k) using the elbow method on the original data.
    - Perform K-Means clustering on the original data.
    - Reduce the data using PCA and identify the optimal number of clusters (k) for the PCA data.
    - Perform K-Means clustering on the PCA data.
    - Visualize the clustering results using scatter plots.
    - Compare the clustering results using elbow curves and composite scatter plots.

## Results

After executing the script, you will obtain the following results:

1. Elbow Curve for Original Data: This plot will show the inertia values for different values of k, helping to identify the optimal number of clusters.

2. Clustered Scatter Plot for Original Data: This plot will display the cryptocurrencies grouped into clusters based on K-Means clustering using the original data.

3. Elbow Curve for PCA Data: This plot will show the inertia values for different values of k for the data reduced using PCA.

4. Clustered Scatter Plot for PCA Data: This plot will display the cryptocurrencies grouped into clusters based on K-Means clustering using the data reduced with PCA.

5. Composite Plots: The script will generate composite plots to contrast the elbow curves and clustered scatter plots for both the original data and PCA data side by side.

## Contributing

If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request. Contributions are welcome!


