# Data Analysis Project

## Overview
This project performs an exploratory data analysis (EDA) and statistical evaluation using Python. It cleans raw data, uncovers key trends, and visualizes actionable insights to support data-driven decision-making.

## Project Structure
```text
├── data/
│   ├── raw/                 # Original, immutable data dumps
│   └── processed/           # Cleaned and transformed datasets
├── notebooks/
│   └── exploratory_analysis.ipynb  # Jupyter notebooks for exploration and visualization
├── src/
│   ├── data_cleaning.py     # Scripts for preprocessing and cleaning data
│   └── analysis.py          # Core analysis and statistical modeling scripts
├── reports/
│   └── figures/             # Generated graphics and plots for reporting
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation
```

## Getting Started

### Prerequisites
* Python 3.8 or higher
* `pip` (Python package installer)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Create and activate a virtual environment (recommended):**
   ```bash
   # On Windows
   python -m venv venv
   venv\Scripts\activate

   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Place your raw dataset inside the `data/raw/` directory.
2. Run the data cleaning script to prepare the dataset:
   ```bash
   python src/data_cleaning.py
   ```
3. Launch Jupyter Notebook to view or run the analysis:
   ```bash
   jupyter notebook notebooks/exploratory_analysis.ipynb
   ```


## Technologies Used
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Statistical Analysis:** SciPy, Statsmodels
* **Environment:** Jupyter Notebook

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
