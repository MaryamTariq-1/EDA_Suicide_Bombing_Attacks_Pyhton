# EDA_Suicide_Bombing_Attacks_Pyhton
###  Pakistan Suicide Bombing Attacks - Exploratory Data Analysis (EDA)

This repository contains the Exploratory Data Analysis (EDA) of the "Pakistan Suicide Bombing Attacks" dataset. The aim of this project is to uncover trends, explore patterns, and provide insights for security policies, preventive measures, peacekeeping, and counter-terrorism strategies.

## Project Overview

The project involves:
- Loading and cleaning the dataset
- Handling missing values
- Performing feature engineering
- Visualizing the data
- Training a simple linear regression model
- Evaluating the model's performance

## Dataset

The dataset used in this project contains information about suicide bombing attacks in Pakistan. The data includes details such as the location, date, number of casualties, and other relevant information.

## File Structure

- `Suicide_bombing_attacks.csv`: The dataset file.
- `Suicide_bombing_attacks.ipynb`: The Python script for performing EDA and training the model.
- `suicide_bombing_attacks_map.html`: An interactive map showing the locations of the attacks.
- `README.md`: This file.

## Requirements

- Python 3.6 or higher
- pandas
- seaborn
- matplotlib
- folium
- scikit-learn

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/MaryamTariq-1/EDA_Suicide_Bombing_Attacks_Pyhton.git
    cd EDA_Suicide_Bombing_Attacks_Pyhton
    ```

2. Install the required packages:
    ```bash
    pip install pandas seaborn matplotlib folium scikit-learn
    ```

## Usage

1. Run the analysis script:
    ```bash
    python Suicide_bombing_attacks.ipynb
    ```

2. Open the interactive map:
    ```bash
    open suicide_bombing_attacks_map.html
    ```

## Exploratory Data Analysis

The EDA includes the following steps:

1. **Data Loading and Cleaning:**
   - Load the dataset and inspect the first few rows.
   - Display summary statistics and check for missing values.

2. **Handling Missing Values:**
   - Fill missing values in categorical and numerical columns appropriately.

3. **Feature Engineering:**
   - Extract additional features such as year, month, and day of the week from the date column.

4. **Visualizations:**
   - Create box plots, histograms, scatter plots, bar plots, and a heatmap to explore the data.
   - Generate an interactive map to visualize the locations of the attacks.

5. **Model Training:**
   - Train a linear regression model to predict the number of casualties based on selected features.
   - Evaluate the model's performance using metrics like Mean Squared Error and R^2 Score.

## Results

The analysis provides insights into the trends and patterns of suicide bombing attacks in Pakistan. The interactive map and visualizations help in understanding the spatial and temporal distribution of the attacks.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Performed Interne At CodexCue!
## Contact

For any questions or inquiries, please contact:
- Your Name: [marymughal216@gmail.com]
- GitHub: [MaryamTraiq-1]

