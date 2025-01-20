# EDA__Analysis
EDA Performance involves thorough analysis of a dataset to uncover insights. It includes data cleaning, univariate and multivariate analyses, correlation studies, and visualizations. 
This repository contains a structured **Exploratory Data Analysis (EDA)** process for analyzing the Global Superstore dataset.

## File Structure
  **`global_superstore_2016.xlsx`**: Dataset file used for analysis.
  **`EDA-performance.ipynb`**: Jupyter Notebook containing the step-by-step EDA process.
  **`README.md`**: Documentation for understanding and navigating the repository.

## Steps Included in EDA Analysis
1. Data Loading
   - Import the dataset into a Pandas DataFrame.
   - Example:
     '''python'''
     df = pd.read_excel('global_superstore_2016.xlsx')

2. Data Cleaning
   - Handle missing values, duplicates, and incorrect data types.

3. Exploratory Data Analysis
   **Univariate Analysis**: Analyze single variables (e.g., sales distribution).
   **Bivariate Analysis**: Explore relationships between two variables (e.g., sales vs profit).
   **Multivariate Analysis**: Study interactions between multiple variables.

4. Visualization
   Use Matplotlib and Seaborn for creating plots like histograms, scatter plots, and heatmaps.

5. Statistical Analysis
    Perform statistical tests to validate insights (e.g., t-tests, ANOVA).

6. Result Interpretation
   - Summarize findings and their implications.

7. Documentation
   Ensure the analysis process and results are well-documented in the notebook.

8. **Presentation**
   Prepare visualizations and summaries for stakeholders.

## Requirements
Install necessary Python libraries:
```bash
pip install pandas numpy seaborn scipy
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook EDA-performance.ipynb
   ```
## License
This project is licensed under the MIT License.
