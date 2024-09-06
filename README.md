# CS Engineers Salary Analysis Dashboard USA (2024)

![image](https://github.com/user-attachments/assets/cb61bfe0-5d17-4136-a8ff-4ddf90ae7979)

This project is a data visualization dashboard built using R and the `flexdashboard` package. It provides insights into the salaries of computer science engineers across the USA for the year 2024.


## Features

- **Highest Paid Job Titles**: A bar graph representing the mean salary for different job titles, allowing users to quickly identify the most lucrative positions.
- **Company Size Distribution**: A pie chart showing the distribution of remote work across different company sizes.
- **Geographical Distribution**: Analysis of the states where most companies are located, providing insights into regional job markets.

## Technologies Used

- **R**
- **flexdashboard**
- **ggplot2**
- **dplyr**

## Installation

To run this dashboard on your local machine, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/your-repository-name.git
2. **Install the necessary R packages: Open R or RStudio and run:**
   ```sh
   install.packages(c("flexdashboard", "ggplot2", "dplyr"))
3. Run the Dashboard: Open the `Code.rmd` file in RStudio and click the "Run Document" button to generate the dashboard.

## Data
The dashboard uses a CSV file (`salaries.csv`) that contains data on job titles, salaries, company sizes, and locations. The data should be placed in the same directory as the `Code.rmd` file for the dashboard to function correctly.

## Usage
The dashboard is designed to be interactive, allowing users to explore the data through various visualizations. It can be used by:

- **Job Seekers:** To identify high-paying job titles and regions with abundant job opportunities.
- **Companies:** To analyze industry salary trends and compare their offerings with market standards.
- **Researchers and Analysts:** To study the distribution of tech jobs across different states and company sizes.
## Contributing
If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License
This project is open-source and available under the MIT License.
