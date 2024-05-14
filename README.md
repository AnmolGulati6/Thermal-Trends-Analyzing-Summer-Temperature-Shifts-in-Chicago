### README File:
```markdown
# Thermal Trends: Analyzing Summer Temperature Shifts in Chicago

## Project Overview
This project investigates the changes in average summer temperatures in Chicago between 2022 and 2023. By analyzing weather data, we explore temperature trends that have implications for urban planning and climate strategy.

## Dataset
The dataset consists of daily maximum temperatures recorded from May to August for the years 2022 and 2023, sourced from Visual Crossing. It includes temperature metrics alongside other relevant meteorological data.

## Tools and Technologies
- **R Programming**: The analysis is conducted in R, utilizing packages like `tidyverse` for data manipulation, `lubridate` for date-time operations, and `ggplot2` for creating visualizations.
- **Libraries Used**: `kableExtra` and `broman` enhance the data presentation, and custom scripts like `viridis.R` and `ggprob.R` assist in advanced graphical outputs.

## Installation
Ensure R and RStudio are installed on your machine. Clone the repository and install the required R packages using:
```R
install.packages(c("tidyverse", "lubridate", "kableExtra", "broman"))
```

## Usage
Run the RMarkdown file `analysis_report.Rmd` to generate the HTML report. The code chunks within this file include data processing and visualization steps that are crucial for understanding the temperature trends.

## Key Analyses
- **Temperature Comparison**: Uses Welch's t-test to compare the mean temperatures between the two summers.
- **Visual Data Summaries**: Line graphs, boxplots, and point plots provide visual summaries of temperature distributions and monthly averages.

## Results
The analysis outputs a detailed report discussing the statistical significance of the temperature change, visual summaries of the data, and implications of these findings.

## Contributing
Contributions to the project are welcome. Please fork the repository and submit pull requests with suggested changes.

## License
Distributed under the MIT License. See `LICENSE` for more information.
