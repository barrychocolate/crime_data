# Crime Data Analysis Project

This project provides tools and methods for analyzing crime data across different regions in the UK. It consolidates crime records from multiple CSV files, calculates summary statistics, and offers breakdowns by crime type and jurisdiction.

## Table of Contents

- [Overview](#overview)
- [Data Requirements](#data-requirements)
- [Project Structure](#project-structure)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Known Issues](#known-issues)
- [Contributing](#contributing)
- [License](#license)

## Overview

The main objectives of this project are:
- To combine multiple CSV files of crime data into a single DataFrame.
- To calculate key statistics, such as the earliest and latest data records and total crime counts.
- To generate breakdowns of crimes by type and jurisdiction.

## Data Requirements

To run this project, you will need to download crime data files from [Data.Police.UK](https://data.police.uk/). Follow these steps:
1. Go to the [Data.Police.UK](https://data.police.uk/) website.
2. Select the specific region(s) and time period of interest.
3. Download the files in CSV format.
4. Save all downloaded files in a folder named `raw_data` in the root directory of this project.

## Project Structure

The main folders in this project are:
- `raw_data`: Contains raw CSV files of downloaded crime data.
- `output_data`: Stores combined and processed data outputs, including `.csv` and `.pkl` files.

## Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/crime-data-analysis.git
   cd crime-data-analysis

2. **Install Required Packages** Make sure you have Python installed. You can install the required packages with:
`pip install -r requirements.txt`
The main libraries used include pandas for data handling and tqdm for progress tracking.

3. Set Up Data
* Download the crime data as described above.
* Place all files in the raw_data folder.

## Usage
1. Run the Jupyter Notebook Start Jupyter Notebook in the project directory:
`jupyter notebook`
Open the crime_data_analysis.ipynb notebook and execute each cell to load data, perform analysis, and save results.

2. Run Data Loading and Processing The notebook will:
* Combine all CSV files in the raw_data folder.
* Calculate and display statistics on the data range, total crime count, and breakdowns by crime type and jurisdiction.
* Save combined data to output_data as both .csv and .pkl files.

## Known Issues
Refer to the [changelog](https://data.police.uk/changelog/) on DATA.POLICE.UK for any known issues with the dataset. Understanding these issues is important to assess the reliability of the data, as certain limitations or errors could impact analysis results.

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.