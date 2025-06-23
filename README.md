# Market Analysis Study with Python Machine Learning

## Project Overview

This project analyzes market and financial stress data using Python-based machine learning and data science techniques. The study includes data cleaning, exploratory data analysis (EDA), clustering, and classification to understand demographic and economic factors affecting financial stress. The analysis is performed using Jupyter notebooks and Python scripts, leveraging libraries such as pandas, scikit-learn, matplotlib, and seaborn.

## Repository Structure & Notebooks

- **eda.ipynb**: Data cleaning, preprocessing, and exploratory data analysis. Includes data import, feature renaming, handling missing values, and initial insights into the dataset's structure and distributions.
- **clustering_comparisons.ipynb**: Applies and compares clustering algorithms (K-Means, Agglomerative, GMM) on demographic and financial data. Outputs cluster summaries and visualizations, and saves results to CSV files.
- **Classification.ipynb**: Builds and evaluates a Random Forest classifier to predict financial stress levels based on demographic and economic features. Includes model training, evaluation, and visualization.
- **hierarchical.py**: Python script for hierarchical (agglomerative) clustering, including preprocessing, PCA, dendrogram visualization, and cluster summary generation.

## Data Files

- **data.csv**: Raw survey data.
- **data_cleaned.csv**: Cleaned and preprocessed version of the raw data.
- **label_encoded_demographic_data.csv**: Label-encoded demographic data for clustering.
- **cluster_representation_summary.csv**: Numeric summary of clusters (means of features).
- **descriptive_cluster_summary.csv**: Mode-based summary of clusters (most common values per cluster).

## Getting Started

1. **Clone the repository**

    ```bash
    git clone https://github.com/Arnold-18-CS/Market-Analysis-Study.git
    ```

2. **Change into the project directory**

    ```bash
    cd Market-Analysis-Study
    ```

3. **Create a virtual environment (Python)**

    ```bash
    python -m venv venv
    ```

4. **Activate the virtual environment**

    - On Windows:

      ```bash
      venv\Scripts\activate
      ```

    - On macOS/Linux:

      ```bash
      source venv/bin/activate
      ```

5. **Install requirements**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

- Open the Jupyter notebooks (`eda.ipynb`, `clustering_comparisons.ipynb`, `Classification.ipynb`) in Jupyter Lab or Jupyter Notebook:

    ```bash
    jupyter lab
    # or
    jupyter notebook
    ```

- Run the cells in order for each notebook. The notebooks are self-contained and will generate outputs, plots, and summary CSVs in the project directory.
- To run the hierarchical clustering script directly:

    ```bash
    python hierarchical.py
    ```

## Main Dependencies

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly
- jupyter

All dependencies are listed in `requirements.txt`.

## License

This project is for educational and research purposes.
