# Exploratory Data Analysis on Iris Dataset

This project provides a comprehensive exploratory data analysis (EDA) of the famous Iris dataset using Python, pandas, seaborn, and matplotlib. The analysis is performed in a Jupyter Notebook ([main.ipynb](main.ipynb)).

## Project Structure

- [main.ipynb](main.ipynb): Jupyter notebook containing all EDA code and visualizations.
- [Iris.csv](Iris.csv): The dataset file.
- [LICENSE](LICENSE): MIT License for the project.
- [.gitignore](.gitignore): Git ignore rules.
- [README.md](README.md): Project documentation.

## Dataset Description

The Iris dataset consists of 150 samples of iris flowers, each described by four features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)
- Species (Iris-setosa, Iris-versicolor, Iris-virginica)

## Analysis Steps

1. **Data Loading & Inspection**
    - Load the dataset using pandas.
    - Display the first few rows, shape, and info.
    - Generate descriptive statistics.

2. **Data Cleaning**
    - Check for missing values.
    - Check for duplicate entries.
    - Remove duplicates if necessary.

3. **Data Exploration**
    - Count the number of samples per species.
    - Visualize species distribution using count plots.

4. **Feature Relationships**
    - Scatter plots for Sepal Length vs Sepal Width and Petal Length vs Petal Width, colored by species.
    - Pair plots for all numeric features.

5. **Distribution Analysis**
    - Histograms for each feature.
    - Distribution plots (distplot) for each feature by species.

6. **Correlation Analysis**
    - Compute Pearson correlation for numeric features.
    - Visualize correlations using a heatmap.

7. **Boxplots**
    - Boxplots for each feature grouped by species.

8. **Outlier Detection & Removal**
    - Use IQR method to detect and remove outliers in Sepal Width.
    - Compare dataset shape before and after outlier removal.

## How to Run

1. **Install Dependencies**
    ```sh
    pip install pandas seaborn matplotlib numpy
    ```

2. **Open Notebook**
    - Open [main.ipynb](main.ipynb) in Jupyter Notebook or Visual Studio Code.

3. **Run Cells**
    - Execute each cell in order to reproduce the analysis and visualizations.

## Visualizations

The notebook includes:
- Count plots
- Scatter plots
- Pair plots
- Histograms
- Distribution plots
- Heatmaps
- Boxplots

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Credits

- Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- Some code adapted from Susobhan Akhuli

---

Feel free to use or modify this analysis for your own learning or projects!