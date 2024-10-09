# Philadelphia Covid Data Explorer

![Alt Philadelphia-Covid-Data-Explorer](./main.jpeg)

## Description
The **Philadelphia Covid Data Explorer** analyzes data from the **OpenDataPhilly portal** and the **US Census Bureau** to provide insights into the COVID-19 pandemic, property assessments, and population statistics for Philadelphia. The tool gives researchers, government officials, and the public a better understanding of the city's demographics and real estate dynamics.

The data sources include:
- **COVID-19 Data**: Information sourced from the Philadelphia Department of Public Health.  
  [Philadelphia Department of Public Health COVID-19 Data](https://www.phila.gov/programs/coronavirus/)
- **Property Data**: Information obtained from the Philadelphia Office of Property Assessment.  
  [Philadelphia Office of Property Assessment](https://www.phila.gov/departments/office-of-property-assessment/)
- **2020 Population Data**: Data for Philadelphia ZIP Codes from the US Census Bureau.  
  [US Census Bureau - Philadelphia ZIP Code Data](https://www.census.gov/quickfacts/fact/table/philadelphiacitypennsylvania/PST045221)


## Features
- Display available actions.
- Show the total population across all ZIP Codes.
- Show the total vaccinations per capita for each ZIP Code.
- Show the average market value for properties in a specific ZIP Code.
- Show the average livable area for properties in a specific ZIP Code.
- Show the total market value of properties, per capita, in a specific ZIP Code.
- View the results of a custom feature.

## How to Run the Project

### Prerequisites:
- **Java 19** or compatible version (check with `java -version`).

### Steps:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/boer-coding/Philadelphia-covid-data-explorer.git
   cd Philadelphia-covid-data-explorer

2. **Unzip data files**:
   ```bash
   unzip data.zip -d ./data

3. **Run the application**:
   ```bash
   java -jar Philadelphia-Covid.jar --population=data/population.csv --log=elog.txt --covid=data/covid_data.csv --properties=data/properties.csv


3. **View logs**:
   ```bash
   cat elog.txt

