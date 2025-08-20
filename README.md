# python_analise_pandas

A collection of Python scripts and notebooks for data analysis using the Pandas library. This project demonstrates various data manipulation, cleaning, visualization, and analysis techniques to help you get the most out of your datasets.

## Features

- Data loading and exploration with Pandas
- Data cleaning (handling missing values, duplicates, and outliers)
- Data transformation and aggregation
- Merging, joining, and concatenating datasets
- Data visualization using Pandas and Matplotlib/Seaborn
- Example workflows for common data analysis tasks

## Getting Started

### Prerequisites

- Python 3.7 or higher
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/) (recommended)
- [seaborn](https://seaborn.pydata.org/) (recommended)
- (Optional) Jupyter Notebook for running notebooks interactively

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Usage

Clone this repository:

```bash
git clone https://github.com/marcojr93/python_analise_pandas.git
cd python_analise_pandas
```

Open and run the scripts or notebooks in your preferred Python environment or Jupyter Notebook.

## Project Structure

```
python_analise_pandas/
├── data/                # Sample data files (if any)
├── notebooks/           # Jupyter Notebooks with analysis examples
├── scripts/             # Standalone Python scripts
├── README.md
└── requirements.txt     # (Optional) List of dependencies
```

## Example

```python
import pandas as pd

# Load a CSV file
df = pd.read_csv('data/sample.csv')

# Display basic info
print(df.info())

# Handle missing values
df = df.dropna()

# Aggregate data
result = df.groupby('category').mean()
print(result)
```

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests for improvements, new examples, or bug fixes.

## License

This project is licensed under the MIT License.

## Author

[marcojr93](https://github.com/marcojr93)