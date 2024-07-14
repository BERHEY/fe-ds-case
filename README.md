# fe-ds-case
Predicting the energy consumption of houses
# F&E Case Study - Data Science

This repository contains the code for the F&E Data Science case study. The goal of this project is to preprocess building data and energy consumption data, and build predictive models to estimate energy consumption.

## Table of Contents
- [Setup](#setup)
- [Usage](#usage)
- [Files](#files)
- [Results](#results)

## Setup

### Prerequisites
- Python 3.8 or higher
- `pip` (Python package installer)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/BERHEY/fe-ds-case.git
    cd fe-ds-case
    ```

2. **Create a virtual environment** (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare the data**:
   - Place your building component data CSV files in the `./data/bauteile` directory.
   - Place your energy consumption data CSV file as `./data/verbrauch/verbrauch.csv`.

2. **Run the analysis**:
   - Open and run `Analysis1.ipynb` in a Jupyter Notebook environment. This notebook contains the complete workflow from data preprocessing to model training and evaluation.

## Files

- `Analysis1.ipynb`: Jupyter Notebook containing the data preprocessing, feature extraction, model training, and evaluation code.
- `requirements.txt`: List of Python packages required to run the notebook.
- `README.md`: This file.

## Results

The results of the model training, including the Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) for different models, are displayed in the final sections of the `Analysis1.ipynb` notebook.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
