# Salt Lithology Model

This project implements a salt lithology model that processes measurement data to determine possible salts based on defined ranges. It includes functionalities for plotting ranges, creating histograms, and analyzing sample data.

## Project Structure

```
salt-lithology-model
├── src
│   ├── __init__.py          # Marks the directory as a Python package
│   ├── model.py             # Main logic for processing measurement data
│   ├── range_plotter.py     # Class for plotting salt measurement ranges
│   ├── histogram.py          # Functions for creating histograms with variable bins
│   └── utils.py             # Utility functions for data processing
├── notebooks
│   └── model.ipynb          # Jupyter notebook for interactive analysis and visualization
├── data
│   └── sample_data.xlsx     # Sample data for testing and analysis
├── tests
│   └── test_histogram.py     # Unit tests for histogram functionality
├── requirements.txt          # List of dependencies for the project
├── .gitignore                # Files and directories to ignore by Git
└── README.md                 # Documentation for the project
```

## Installation

To set up the project, clone the repository and install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Load the sample data from `data/sample_data.xlsx`.
2. Use the functions in `model.py` to process measurement data.
3. Utilize the `RangePlotter` class in `range_plotter.py` to visualize salt measurement ranges.
4. Create histograms using the `Histogram` class or functions in `histogram.py` to analyze the frequency of salts found in samples.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for details.