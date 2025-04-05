---

# Querying EPA Data

## Overview

This repository contains a suite of reproducible scripts and tools to query, download, clean, and analyze emissions and compliance data from the U.S. Environmental Protection Agency’s **Clean Air Markets Division (CAMD)**. The tools are designed for use in R and leverage the official [EPA CAMD API](https://campd.epa.gov/) to retrieve structured datasets.

These datasets cover key U.S. air pollution trading programs, including:

- **Acid Rain Program (ARP)**
- **Cross-State Air Pollution Rule (CSAPR)**
- **California NOₓ Budget Trading Program (CSNOX)**

This project facilitates historical emissions tracking, allowance holdings analysis, facility-level compliance evaluation, and high-quality visualization of data across these programs.
## Project Structure

```
Querying_EPA_Data/
├── README.md                # Project overview and instructions
├── LICENSE                  # Open-source license file
├── .gitignore               # Files and folders to ignore in Git
├── Querying_EPA_Data.Rproj  # RStudio project file
│
├── Data/                    # Raw and processed data
│   ├── Raw/                 # Original datasets downloaded from the EPA CAMD API
│   ├── Processed/           # Cleaned and transformed datasets used in analysis
│
├── Scripts/                 # Analysis scripts and RMarkdown documents
    ├── 01_Query_Facility_Data.Rmd        # Query and process facility data
    ├── 02_Query_Allowance_Holdings.Rmd   # Query and process allowance holdings data
    ├── 03_Query_Annual_Emissions.Rmd       # Query and process annual emissions data

```
Supported EPA Programs

This repository supports programmatic access to and analysis of three major EPA emissions control programs:

Acid Rain Program (ARP): Established under Title IV of the Clean Air Act Amendments of 1990, the ARP regulates sulfur dioxide (SO₂) and nitrogen oxides (NOₕ) emissions from fossil fuel-fired power plants across the United States. It was the first large-scale cap-and-trade program for air pollution in the world.

Cross-State Air Pollution Rule (CSAPR): This program targets the reduction of emissions that contribute to ozone and fine particulate matter (PM2.5) pollution in downwind states. It establishes emissions budgets and allowance markets for both SO₂ and NOₕ across multiple regions.

Cross-State Air Pollution NOₓ (CSNOX): This program is designed to limit summertime NOₕ emissions from major sources in California. The CSNOX program plays an important role in the state's ozone attainment and regional air quality plans.

## How to Use

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/robertjdellinger/querying-epa-data.git
   cd querying-epa-data
   ```

2. **Open the Project in RStudio:**

   Open the `querying-epa-data.Rproj` file to start your analysis in RStudio.

3. **Data Organization:**

   - Place any new raw data files in the `Data/Raw/` folder.
   - Processed data can be saved in the `Data/Processed/` folder.

4. **Run the Scripts:**

   Execute the RMarkdown documents located in the `Scripts/` folder in sequential order:
   - Start with `01_Query_Facility_Data.Rmd` to download and process facility data as well as visualize facility locations on an interactive map.
   - Continue with `02_Query_Allowance_Holdings.Rmd` and `03_Query_Annual_Emissions.Rmd` for other datasets.

## Data Sources

United States Environmental Protection Agency (EPA). “Clean Air Markets Program Data.” Washington, DC: Office of Atmospheric Protection, Clean Air Markets Division. Available from EPA’s Air Markets Program Data web site: https://campd.epa.gov/.

United States Environmental Protection Agency (EPA). “Power Sector Data.” Washington, DC: Office of Atmospheric Protection, Clean Air and Power Division. Available from EPA’s Clean Air Markets Program Data website: https://campd.epa.gov.

For more information on these data sources, visit the official [EPA CAMPD website](https://campd.epa.gov/).

## Contact

For questions or further information, please contact:

**Robert J. Dellinger**  
Ph.D. Student, Atmospheric & Oceanic Sciences, UCLA  
Email: rjdellinger[at]ucla.edu  
GitHub: [rob-dellinger](https://github.com/rob-dellinger)

---

Feel free to modify the content above to match your repository details and workflow. This README provides a clear overview of the project structure, usage instructions, data sources, and contact information.