# Analyzing COVID-19 Vaccination Trends

This project focuses on analyzing COVID-19 vaccination trends globally and by region, using official WHO vaccination datasets. The analysis includes tracking vaccination progress, exploring vaccine distribution, and analyzing trends in vaccination adoption rates across various regions and countries.

**This is the first project made under the series of "Exploring Data Science for Public Health."**

## Objectives

- Explore global vaccination trends using **Pandas**.
- Visualize quarterly vaccination progress using **Matplotlib**.
- Compare vaccination rates across **countries** and **WHO regions**.

## Data Sources

The datasets used in this project include:

1. **WHO COVID-19 Vaccination Data**: Contains vaccination metrics such as total vaccinations, people vaccinated with 1+ dose, booster doses, etc.
2. **COVID-19 Vaccine Introduction Data**: Includes information on vaccine types, companies, and vaccination introduction timelines.

Additional data processing is applied to align countries with their corresponding WHO regions and analyze vaccination trends accordingly.

## Features of the Project

1. **Global Vaccination Trends**:
   - Analyze the global vaccination progress and visualize it over time.
  
2. **Regional Comparison**:
   - Compare vaccination rates across different WHO regions such as AFRO, AMRO, EURO, SEARO, WPRO, and EMRO.
  
3. **Country-Specific Analysis**:
   - Dive into the vaccination progress for selected countries such as the USA, India, Brazil, and the UK.
  
4. **Vaccine Introduction Trends**:
   - Track the introduction of different vaccines globally using the introduction start and end dates.

5. **Booster Dose Adoption Rates**:
   - Analyze the adoption of booster doses in various countries and regions.

## Getting Started

### Prerequisites

To get started, you will need the following Python libraries:

- **Pandas**
- **Matplotlib**
- **NumPy**

### Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/Srayoshi-Mirza/Analyzing-COVID-19-Vaccination-Trends-Updated-Quarterly-.git
cd covid-vaccine-analysis
```

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

### Data Files

Make sure you have the following data files in the `/data` folder of the project:

  **1. vaccination-data.csv**: Contains vaccination data across countries and regions.

  **2. vaccine-introduction-data.csv**: Contains data on vaccine types, companies, and introduction dates.

## Data Processing

The project processes and cleans data to make it suitable for analysis:

- **Handling Missing Data**: Missing numeric values are filled with zeros, and categorical values are filled with 'Unknown.'
- **Quarterly Resampling**: The data is resampled quarterly to observe vaccination trends over time.
- **WHO Region Lookup**: ISO3 country codes are mapped to their respective WHO regions to facilitate region-based analysis.

## Visualizations

- **Vaccination Trends**: Line plots showing vaccination progress over time (quarterly).
- **Vaccine Type Distribution**: Stacked bar charts illustrating the types of vaccines used across countries.
- **Booster Dose Adoption**: Bar charts comparing booster dose adoption rates across countries and regions.

## Example Outputs

- **Quarterly Vaccination Trends**: Track the vaccination progress over time for selected countries and regions.
- **Booster Dose Adoption Rates**: Visualize how booster doses are being adopted across different countries and regions.
