<div align="center">
  <a href="https://www.linkedin.com/in/melekncci/" target="_blank">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=normal&logo=linkedin&logoColor=white" style="vertical-align:center" />
  </a>
</div>

# Breast-Cancer-Anomaly-Detector

The **Breast-Cancer-Anomaly-Detector** is a Python-based tool designed to identify patients with unusual characteristics within breast cancer diagnosis data. This anomaly detection system focuses on identifying data points that significantly deviate from normal patterns, providing insights into potential health issues related to breast cancer.

## Features

- **Anomaly Detection**: Identifies patients exhibiting distinct characteristics based on breast cancer diagnosis data.
- **Customizable**: Adjust and fine-tune the detection system based on the number of anomalies expected by experimenting with parameters.

## Dataset

The dataset `patients.csv` includes:
- **310 records** of individuals, each described by **30 different features** related to breast cancer diagnosis.
- The dataset contains both healthy individuals and those with significant deviations.

## Project Structure

The project is organized into several key phases:

### 1. Data Exploration
- **Loading and Examining Data**: Initial examination of the dataset.
- **Basic Statistics**: Calculation of statistics for each feature.
- **Feature Distributions**: Investigation using histograms.

### 2. Data Preprocessing and Visualization
- **Normalization**: Ensuring consistent scales across features.
- **Visualization**: Scatter plots and PCA for dimensionality reduction.

### 3. Calculating Euclidean Distance
- **Distance Calculation**: Function to compute Euclidean distance between data points.

### 4. Anomaly Score Calculation
- **Anomaly Scores**: Method to compute scores based on distances to k-nearest neighbors.

### 5. Identifying Anomalies
- **Detection**: Identifying the most anomalous patients using the computed scores.

### 6. Visualization of Anomalies
- **Visual Representations**: Highlighting and comparing anomalous and normal data points.

## Results

The anomaly detection system successfully identifies patients with unusual characteristics, which may indicate potential health issues. The system's parameters can be adjusted based on the expected number of anomalies to fine-tune its performance.

## Visualization

- **Histograms**: Display the distribution of each feature.
- **Scatter Plots**: Visualize anomalies in a reduced feature space (e.g., after PCA).
- **Anomaly Score Distribution**: Highlight patients with the highest anomaly scores.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please feel free to fork the repository and submit a pull request.

## Screenshots

![1](https://github.com/user-attachments/assets/df765b4d-8534-4221-959c-2126c84253cb)
![2](https://github.com/user-attachments/assets/126a9b79-51ee-4673-b7bd-80eb6dbc9c68)
![3](https://github.com/user-attachments/assets/1adeb1e9-ad06-4ff9-9bf0-d442423c0208)
![4](https://github.com/user-attachments/assets/8c407adb-400e-43d9-ad19-ed13c86f9ff8)
![5](https://github.com/user-attachments/assets/e897fa11-a9ef-4474-bffd-0960a028e892)

## Tech Used

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

[Contact me on LinkedIn!](https://www.linkedin.com/in/melekncci/)
