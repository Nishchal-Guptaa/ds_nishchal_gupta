# Fear and Greed Index and Historical Trading Data Analysis

This project explores the relationship between the cryptocurrency Fear and Greed Index and historical trading data using two datasets: `fear_greed_index.csv` and `historical_data.csv`.

## Project Structure

The project is structured as a Google Colab notebook with the following sections:

1. **Data Loading and Initial Inspection**: 
   - Loading the datasets into pandas DataFrames and examining their structure, data types, and basic statistics.

2. **Data Cleaning and Preparation**: 
   - Handling missing values, outliers, and inconsistencies in the data. 
   - Converting data types as necessary.

3. **Exploratory Data Analysis (EDA)**: 
   - Conducting exploratory data analysis to uncover patterns, relationships, and trends within each dataset using visualizations and statistical summaries.

4. **Feature Engineering**: 
   - Creating new features from existing ones to enhance the analysis.

5. **Combine and Analyze Data**: 
   - Merging the two datasets based on relevant keys and analyzing the combined data to find correlations or differences between the datasets.

## Datasets

- **`fear_greed_index.csv`**: Contains historical data of the Fear and Greed Index.
- **`historical_data.csv`**: Contains historical trading data.

## Analysis Highlights

- Initial inspection of both datasets to understand their structure and content.
- Handling of missing values and outliers to ensure data quality.
- Exploratory data analysis using histograms, count plots, and scatter plots to visualize the distributions and relationships within each dataset.
- Feature engineering to extract relevant information (e.g., day of the week, month, hour of day, profit/loss).
- Merging the two datasets based on date to enable combined analysis.
- Calculating and visualizing the correlation matrix of the combined data.
- Exploring the relationship between the Fear/Greed Index and trading metrics through scatter plots and time series plots.

## Potential Further Analysis

Based on the initial analysis, further exploration could include:

- Analyzing trader behavior by different Fear/Greed Index classifications.
- Conducting time series analysis of the relationship between the Fear/Greed Index and trading metrics.
- Performing statistical significance testing on observed relationships.
- Building regression models to quantify the impact of market sentiment on trading outcomes.
- Simulating sentiment-based trading strategies.

## How to Run the Notebook

1. Upload the `fear_greed_index.csv` and `historical_data.csv` files to your Google Drive or the Colab environment.
2. Open the notebook in Google Colab.
3. Run the cells sequentially to execute the data loading, cleaning, analysis, and visualization steps.

## Dependencies

The project uses the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

These dependencies are typically pre-installed in Google Colab environments.
