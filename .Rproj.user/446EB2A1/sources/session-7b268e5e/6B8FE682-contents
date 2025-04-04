---

# Querying EPA CAMD Data

## Overview

This repository contains a comprehensive suite of scripts and tools to query, download, and analyze data from the U.S. Environmental Protection Agency’s Clean Air Markets Division (CAMD). The repository covers multiple data types including facility data, allowance holdings, and annual emissions. All analyses and visualizations are performed in R using reproducible RMarkdown documents.

## Repository Structure

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
│   ├── 01_Query_Facility_Data.Rmd        # Query and process facility data
│   ├── 02_Query_Allowance_Holdings.Rmd   # Query and process allowance holdings data
│   ├── 03_Query_Annual_Emissions.Rmd       # Query and process annual emissions data
│   └── Functions/                         # Custom functions for reuse
│         └── Helper_Functions.R          # Helper functions (e.g., API calls, data cleaning)
│
├── Output/                  # Generated figures, tables, and reports
    ├── Figures/             # Visualizations and maps
    ├── Reports/             # Final reports and manuscripts
    └── Tables/              # Summary tables and analytical results

```

## How to Use

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/Querying_EPA_Data.git
   cd Querying_EPA_Data
   ```

2. **Open the Project in RStudio:**

   Open the `Querying_EPA_Data.Rproj` file to start your analysis in RStudio.

3. **Data Organization:**

   - Place any new raw data files in the `Data/Raw/` folder.
   - Processed data will be saved in the `Data/Processed/` folder.
   - Analysis outputs (e.g., figures, tables, reports) will be written to the `Output/` directory.

4. **Run the Scripts:**

   Execute the RMarkdown documents located in the `Scripts/` folder in sequential order:
   - Start with `01_Query_Facility_Data.Rmd` to download and process facility data.
   - Continue with `02_Query_Allowance_Holdings.Rmd` and `03_Query_Annual_Emissions.Rmd` for other datasets.
   - Finally, use `04_Map_Facilities.Rmd` to visualize facility locations on an interactive map.

5. **Review Documentation:**

   For detailed methodology and references, see `Docs/Methodology.Rmd` and the `Docs/References/` folder.

## Data Sources

Data is retrieved from the EPA’s Clean Air Markets Program Data (CAMPD) API, which includes:
- **Facility Data:** Detailed attributes and operational information for regulated facilities.
- **Allowance Holdings Data:** Information on allowances allocated under market-based emissions programs.
- **Annual Emissions Data:** Historical emissions records covering various programs (e.g., Acid Rain Program, Cross-State Air Pollution Rule).

For more information on these data sources, visit the official [EPA CAMPD website](https://campd.epa.gov/).

## Publication-Quality Visualizations

The repository also includes scripts for creating publication-quality visualizations, including:
- Bar graphs that summarize total allowances by vintage year.
- Interactive maps of facility locations using the **leaflet** package, enhanced with custom markers and clustering.

## Contact

For questions or further information, please contact:

**Robert J. Dellinger**  
Ph.D. Student, Atmospheric & Oceanic Sciences, UCLA  
Email: rjdellinger[at]ucla.edu  
GitHub: [rob-dellinger](https://github.com/rob-dellinger)


# Citations

United States Environmental Protection Agency (EPA). “Clean Air Markets Program Data.” Washington, DC: Office of Atmospheric Protection, Clean Air Markets Division. Available from EPA’s Air Markets Program Data web site: https://campd.epa.gov/.

United States Environmental Protection Agency (EPA). “Power Sector Data.” Washington, DC: Office of Atmospheric Protection, Clean Air and Power Division. Available from EPA’s Clean Air Markets Program Data website: https://campd.epa.gov.


---

Feel free to modify the content above to match your repository details and workflow. This README provides a clear overview of the project structure, usage instructions, data sources, and contact information.