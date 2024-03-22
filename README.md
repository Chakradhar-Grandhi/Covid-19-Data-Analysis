
# Covid-19 Data Analysis and Visualizations

This project is a comprehensive analysis of COVID-19 data, focusing on various metrics such as confirmed cases, recoveries, deaths, and active cases across different countries. The analysis includes data cleaning, processing, and visualizations to gain insights into the pandemic's impact globally.

## Project Structure

- **Covid_19_Data_Analysis.ipynb**: The main Jupyter notebook containing the code for data loading, processing, and visualization.
- **Dataset/**: Directory containing the CSV files used for analysis. Ensure the data files are correctly placed here.

## Prerequisites

To run the notebook, you will need the following Python libraries:

- `pandas`
- `matplotlib`
- `seaborn`
- `geopandas`
- `geoplot`
- `cartopy`
- `contextily`

You can install these libraries using `pip`:

```bash
pip install pandas matplotlib seaborn geopandas geoplot cartopy contextily
```

## Data Sources

The data used in this analysis is sourced from publicly available COVID-19 datasets. Ensure you have the necessary CSV files in the `./Dataset/` directory.

## Analysis Overview

The notebook covers the following key aspects:

1. **Data Loading and Preprocessing**: Reads the COVID-19 data from CSV files, handles missing values, and performs necessary transformations.

2. **Data Visualization**: 
   - Time series plots to track the progression of the pandemic.
   - Geographical visualizations to understand the spread across different regions.
   - Comparative analysis between countries.

3. **Subsetting Data**: Focuses on creating subsets of the data for specific analyses, such as evaluating changes in the death toll over time.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/covid-19-data-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd covid-19-data-analysis
    ```
3. Ensure that the necessary datasets are placed in the `./Dataset/` directory.
4. Open the Jupyter notebook:
    ```bash
    jupyter notebook Covid_19_Data_Analysis.ipynb
    ```
5. Run the notebook cells sequentially to perform the analysis.

## Results

The notebook provides various insights into the COVID-19 pandemic, including visualizations that showcase the trends in confirmed cases, recoveries, deaths, and more. These insights can be used for further analysis or as a reference for understanding the pandemic's progression.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
