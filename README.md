# South Korea Tourism Analysis: Visitor Trends and Demographics

This project analyzes longitudinal tourism data to understand seasonal trends, visitor demographics, and the impacts of global events on South Korea's inbound tourism. The analysis is conducted in Python using Jupyter Notebooks and covers research questions using data wrangling, exploratory data analysis, hypothesis testing, and time series analysis.

### Download the Dataset
The raw data for this project was sourced from the **Korea Tourism Knowledge Information System**:
https://know.tour.go.kr/english.do

*Note: The `Master_Tourism_Data_2013_2021.zip` file contains the fully processed dataset ready for the main analysis. The raw Korean `.xlsx` file and the `ICS604_final_pre_process_wb.ipynb` notebook are included purely for transparency, in case you wish to see how the master dataset was compiled from scratch.*

### Folder Structure
```text
.
├── requirements.txt                              # Required python packages with versions 
├── ICS604_final_project_behrens.ipynb            # Main analysis notebook
├── ICS604_final_pre_process_wb.ipynb             # Data cleaning/compilation notebook
├── ICS604_Behrens_final_project_report.pdf       # Final written report
├── Master_Tourism_Data_2013_2021.zip             # Processed master dataset (ready to use)
├── 2016.05 방한외래관광객 세부통계.xlsx          # Sample raw data file used for preprocessing
└── README.md                                     # Project documentation
```
### Environment Setup
This project uses `uv` for lightning-fast dependency management. To set up your virtual environment and install the required packages, run:

```bash
uv pip install -r requirements.txt
```
### Running the Notebook

Once your environment is set up and activated, you have two options to run the analysis:

**Option 1: Jupyter in the Browser**

Launch Jupyter directly from your terminal:
```bash
jupyter notebook
```
**Option 2: Visual Studio Code**

Open the project folder in VS Code and click on ```ICS604_final_project_behrens.ipynb```. Ensure your ```uv``` environment (e.g., ```.venv```) is selected by clicking Select Kernel in the top right corner, then run the cells sequentially.
