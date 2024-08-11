# Doodle Data Visualization and Processing

This project is a Python-based tool designed to visualize and process doodle data from CSV files. It compares original and processed doodles by applying shape regularization techniques such as Gaussian smoothing. This tool is ideal for analyzing complex doodle datasets and can be easily adapted for various types of doodle data.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project provides a powerful tool for visualizing doodle data by loading, processing, and comparing doodles from CSV files. The main feature of this tool is its ability to apply a smoothing process to the doodles, making the shapes more uniform and easier to analyze.

## Features

- **Data Loading**: Reads and organizes doodle data from CSV files.
- **Shape Processing**: Applies Gaussian smoothing to regularize doodle shapes.
- **Visualization**: Compares original and processed doodles side-by-side.
- **Adaptability**: Easily customizable for different datasets and processing techniques.

## Installation

### Prerequisites

- Python 3.x
- Required Python packages: `numpy`, `matplotlib`, `scipy`

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/doodle-visualization.git
    ```

2. Change to the project directory:

    ```bash
    cd doodle-visualization
    ```

3. Install the required Python packages:

    ```bash
    pip install numpy matplotlib scipy
    ```

## Usage

### Running the Tool

1. Place your CSV file(s) containing the doodle data in the project directory.

2. Modify the `csv_file` variable in the script to point to your CSV file:

    ```python
    csv_file = "/path/to/your/csvfile.csv"
    ```

3. Run the script using the following command:

    ```bash
    python doodle_visualization.py
    ```

### Expected Output

The tool will generate a side-by-side comparison of the original and processed doodles, displayed using Matplotlib. The processed doodles will be smoothed versions of the original data.

## Customization

- **Smoothing Level**: Adjust the `sigma` parameter in the `process_shape` function to control the level of smoothing. Higher values will result in more smoothing.
- **Visualization**: Customize the colors and styles used in the plots by modifying the `plot` function.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
