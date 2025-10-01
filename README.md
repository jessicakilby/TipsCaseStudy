# 📊 Tips Case Study
        
## Project Overview

This case study analyzes tipping behavior at Chef’s Kitchen, a popular San Diego restaurant known for excellent service. As the Data Analyst, my goal is to uncover patterns in customer tips and revenue across demographics using exploratory analysis and visualizations. The insights will help the restaurant better understand guest behavior and optimize service strategies.
        
## Structure
- `data/`: Raw and cleaned datasets
- `venv/`: Virtual environment
- Jupiter Notebook: ETL, reporting logic, exploratory analysis and visualizations
        
## Setup Instructions
1. Clone the repo or copy the folder
2. Create and activate the virtual environment:
    python -m venv venv venv\Scripts\activate
3. Install dependencies:
    pip install -r requirements.txt
        
## Key Scripts
- `Tips_Case_Study.ipynb`: This Jupyter Notebook contains the full workflow for the project, including data import, cleaning, exploration, and analysis. It addresses core business questions using Python libraries such as pandas, matplotlib, and seaborn, and presents insights to support strategic decisions around restaurant demand and customer experience.

> **Disclaimer**: The Markdown content and analytical workflow within the notebook were provided by Great Learning as part of their instructional material. This includes the structure, prompts, and guiding questions for the analysis. All Python code cells, data cleaning, and exploratory work were authored independently.
        
        
## Notes
- Data source: `tips.csv`
- Contact: Jessica Kilby ([jessicakilby@gmail.com](mailto:jessicakilby@gmail.com))


## Progress Log

### October 1, 2025 – Visualization & Insight Refinement

- Created and customized pair plots and regression plots to explore relationships between `Total Bill` and `Tip Amount`, segmented by `Sex` and `Smoker` status.
- Renamed axis labels for clarity and presentation polish.
- Interpreted correlation coefficients and visual patterns, noting strong positive relationships between bill size and tip amount.
- Identified behavioral trends, such as higher spending and tipping among male customers at non-smoking tables.
- Updated `.gitignore` to exclude `Info/` folder and resolved Git tracking issues.
