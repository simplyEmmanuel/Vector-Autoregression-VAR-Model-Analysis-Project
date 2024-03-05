# Vector-Autoregression-VAR-Model-Analysis-Project
The study examines the intricate dynamics between unemployment rates, federal funds rates, and the Consumer Price Index (CPI), pivotal indicators of economic health and policy effectiveness.

### Project Overview:
This repository contains an R Markdown file and its corresponding HTML output detailing a Vector Autoregression (VAR) analysis of key economic indicators: the Consumer Price Index (CPI), unemployment, and federal funds rates. The project aims to forecast economic trends and understand the interaction between these variables.

This research project employed the Vector Autoregression (VAR) model to analyze the dynamic relationship between key economic indicators: the Consumer Price Index (CPI), unemployment, and federal funds rates. The project aims to forecast short-term economic trends by understanding the intricate interplay of these variables.

### Key Features:
  - **Data Acquisition:** Scripts to fetch and preprocess monthly economic data from the Federal Reserve Economic Data (FRED).
  - **VAR Model Development:** Implemented a VAR model in R to identify and quantify the relationships among the CPI, unemployment, and federal funds rates.
  - **Model Validation:** ACF and PACF plots to ensure the model’s residuals are white noise, suggesting a good fit.
  - **Forecasting:** Predictive analysis using the VAR model to forecast the CPI for a three-month horizon, focusing on detecting potential inflationary pressures.
  - **Visualization:** A series of plots demonstrating actual data trends and predictive forecasts to visualize the model's insights.
  - **Research Insights:** The repository showcases a complete workflow for VAR model analysis, from data sourcing to predictive forecasting, providing valuable insights into the potential impacts of employment and policy changes on inflation.

### Usage:
This project is ideal for economists, data scientists, and policymakers interested in advanced economic modeling and forecasting. The code and methodologies can be adapted for similar economic data and analysis. 

## Viewing the Project
To view the HTML output of the project directly in your web browser, follow these steps:
1. Navigate to the `HTML_output` file in the repository.
2. Click on the file to open it.
3. View the raw HTML file using the "Raw" button.

## Running the R Markdown File
To run the `.Rmd` file, you will need to have R and RStudio installed or use a cloud-based R environment.

### Local Installation
#### Install R
1. Go to [CRAN](https://cran.r-project.org/) and download your operating system's latest version of R.
2. Follow the installation instructions for your OS.

#### Install RStudio
1. Visit the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download).
2. Download and install the version of RStudio appropriate for your system.

#### Run Rmd
1. Open RStudio.
2. Install the required R packages using `install.packages("packageName")`.
3. Open the `.Rmd` file from this repository.
4. Click the "Knit" button in RStudio to render the document and view the output.

### Cloud-Based Tools
If you prefer not to install software locally, you can use cloud-based services like [RStudio Cloud](https://rstudio.cloud/) to run R Markdown files. Simply upload the `.Rmd` file to the service and proceed to knit as above.

### Contributions:
Contributions are welcome, especially in the areas of model refinement, data visualization, and forecasting accuracy.  Please fork the repository, make changes, and submit a pull request.
