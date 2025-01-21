# Monitoring Data Quality with Great Expectations

This repository contains a Jupyter notebook demonstrating how to monitor data quality using the **Great Expectations** library. The example provided uses a simple dataset to validate specific conditions, ensuring that the data meets the required quality standards.

## Contents

- `Notebooks/`
  - `Monitoring_Data_Quality.ipynb`: The main notebook demonstrating data quality checks.
- `data/`
  - `updated_trial_Dataset1.csv`: The dataset used for validation.
  - `cities.txt`: A file containing valid location data.
- `requirements.txt`: Lists all Python dependencies required to run the notebook.
- `.gitignore`: Specifies intentionally untracked files to ignore.

## Getting Started

### Prerequisites

Ensure you have Python installed. It is recommended to use a virtual environment to manage dependencies.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/data-quality-monitoring.git
    cd data-quality-monitoring
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Start Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

4. Open `Notebooks/Monitoring_Data_Quality.ipynb` in the Jupyter interface.

## Usage

Run the cells in the notebook to see how data quality checks are performed using Great Expectations. The notebook reads `updated_trial_Dataset1.csv` and validates it against the conditions defined, using `cities.txt` for location data validation.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- **Great Expectations**: For providing the library used in this project.
