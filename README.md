# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using various data visualization techniques and machine learning models.

## Project Overview

Credit card fraud detection is a critical issue in the financial sector. This project leverages data analysis and visualization to understand patterns in the dataset and identify potential fraudulent transactions.

## Dataset

The dataset used for this project can be downloaded from the following link:
[Credit Card Fraud Detection Dataset](https://drive.google.com/file/d/1OrAvByf5vvRbrOR8LBHiIrArmIagjR9m/view?usp=sharing)

### Dataset Description

- **Time**: The time elapsed between this transaction and the first transaction in the dataset (in seconds).
- **V1-V28**: The result of a PCA transformation. Due to confidentiality issues, the original features are not provided.
- **Amount**: The transaction amount.
- **Class**: The class label, where 1 indicates a fraudulent transaction and 0 indicates a genuine transaction.

## Project Structure

```
├── data
│   └── creditcard.csv
├── notebooks
│   └── Credit_Card_Fraud_Detection.ipynb
├── README.md
└── requirements.txt
```

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from the link provided above and place it in the `data` directory.

## Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/Credit_Card_Fraud_Detection.ipynb
   ```

2. Run the cells in the notebook to perform data analysis, visualization, and fraud detection.

## Visualizations

### 1. Plot Per Column Distribution

This function visualizes the distribution of each feature in the dataset.

### 2. Correlation Matrix

This function plots the correlation matrix to identify relationships between features.

### 3. Scatter Matrix

This function plots a scatter matrix for a pairwise comparison of features.

### 4. Fraud Detection Bar Graph

This function plots the count of fraudulent and non-fraudulent transactions.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

This project was created by Pranav Shukla. 

---

