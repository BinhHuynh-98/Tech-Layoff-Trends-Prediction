# Tech Company Layoffs Analysis

This project analyzes technology company layoffs data to provide insights into industry trends, geographical impact, and the relationship between company status and layoff severity.

## Project Overview

The analysis focuses on three main aspects:
1. Temporal trends in tech layoffs
2. Geographical distribution of layoffs
3. Impact of company IPO status on layoff patterns

## Dataset

The analysis uses the `tech_layoffs(1).csv` dataset, which contains information about:
- Company names
- Number of employees laid off
- Impacted workforce percentage
- Reporting dates
- Industry classifications
- Headquarters locations
- Company IPO status
- Additional contextual information

## Requirements

To run this analysis, you need:

```
Python 3.x
Jupyter Notebook
pandas
numpy
matplotlib
seaborn
scipy
```

## Installation

1. Ensure you have Anaconda or Miniconda installed
2. Create and activate a new environment:
```bash
conda create -n tech_layoffs python=3.8
conda activate tech_layoffs
```

3. Install required packages:
```bash
conda install pandas numpy matplotlib seaborn scipy jupyter
```

## Usage

1. Clone or download this repository
2. Navigate to the project directory
3. Launch Jupyter Notebook:
```bash
jupyter notebook
```
4. Open `tech_layoffs_analysis.ipynb`
5. Run all cells in sequence

## Analysis Components

### 1. Monthly Trends
- Visualization of layoff patterns over time
- Identification of peak layoff periods
- Monthly aggregation of total layoffs

### 2. Location Analysis
- Ranking of most impacted locations
- Distribution of affected companies by location
- Geographical concentration of layoffs

### 3. IPO Status Analysis
- Comparison between public and private companies
- Statistical testing for significance
- Distribution analysis of layoff sizes by company status

## Results

The notebook generates various visualizations and statistical analyses:
- Bar charts showing temporal trends
- Geographic distribution visualizations
- Comparative analysis between public and private companies
- Statistical significance tests

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional analyses.

## License

This project is open source and available under the MIT License.

## Contact

For questions or suggestions, please open an issue in the repository. 