# Analysis of Malaria in the Western Amazon: A Time Series Analysis (2012-2023)

This repository contains the data and R script used for the analysis of temporal trends, sociodemographic profiles, and hospitalization costs of malaria cases in the Brazilian Western Amazon from 2012 to 2023.

The main objective is to ensure the **transparency and reproducibility** of the results presented in the manuscript by providing access to all analysis materials.

## Repository Structure

The repository is logically organized to facilitate navigation and understanding of the workflow:

* **`data/`**: Contains the datasets used. The `processed/` folder includes clean, organized files by topic (costs, mortality, and prevalence), ready for analysis.
* **`scripts/`**: Stores the R script (`analysis_r.R`), which performs all steps of the statistical analysis, from data manipulation to the generation of plots and tables.
* **`outputs/`**: Holds the analysis results, such as trend plots and results tables.
* **`README.md`**: This file, which serves as a guide to the repository's content.

## How to Reproduce the Analysis

To run the code and replicate the analyses, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone <your repository URL>
    ```

2.  **Install R and Necessary Packages:**
    Make sure you have the R programming environment installed. Then, run the following command in the R console to install the required libraries:
    ```R
    install.packages(c("readxl", "dplyr", "prais", "ggplot2", "tidyr", "scales", "geobr", "sf"))
    ```

3.  **Run the Script:**
    Open the `scripts/analysis_r.R` file in RStudio and execute it. The script will process the data and generate the results in the corresponding folders.

## About the Analysis

The study uses **Prais-Winsten regression** for time series analysis, a robust technique for autocorrelated data. The analyses focus on four sociodemographic categories: regional, sex, age group, and color/race, allowing for a detailed understanding of malaria dynamics in the region.

## Contact

For questions, suggestions, or collaborations, feel free to open an issue in this repository or contact the corresponding author of the manuscript:

### Pedro Omar Batista Pereira
<pedro.omar@sou.ufac.br>

## License

This project is licensed under the **MIT License**. For more details, see the `LICENSE` file.
