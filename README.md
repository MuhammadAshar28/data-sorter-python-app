# Data Sorter

# Live Demo: https://data-sorter.streamlit.app/

## Overview
Data Sorter is a Python application designed to efficiently sort data from various file formats, including CSV, and excel files. It provides users with an easy-to-use interface for organizing and structuring data based on different sorting criteria.

## Features
- Supports sorting of CSV, xls files.
- Allows sorting based on multiple columns or keys.
- Provides ascending and descending order sorting options.
- Outputs sorted data in the same or a different file format.
- Simple command-line interface for ease of use.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-sorter.git
   cd data-sorter
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the script from the command line:
```bash
python sorter.py --file data.csv --column name --order asc
```

### Arguments:
- `--file`: Specifies the input file (CSV, JSON, TXT).
- `--column`: Defines the column/key to sort by (for structured data like CSV or JSON).
- `--order`: Specifies sorting order (`asc` for ascending, `desc` for descending).
- `--output`: (Optional) Output file name, defaults to overwriting the input file.

### Example Usage:
Sort a CSV file by the "price" column in descending order:
```bash
python sorter.py --file products.csv --column price --order desc --output sorted_products.csv
```


## Contributing
Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request with your improvements.

## License
This project is licensed under the MIT License.


