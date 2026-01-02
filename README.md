# Global AI Adoption Patterns

Analysis of AI usage patterns across emerging and developed markets using Anthropic's Economic Index dataset.

## Key Finding

Emerging markets show **4-6 percentage points higher automation rates** compared to developed markets, suggesting different AI adoption patterns based on economic development.

## Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/Rsiddharth54/Global_AI_Adoptions_Claude.git
cd Global_AI_Adoptions_Claude
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the analysis
```bash
jupyter notebook notebooks/analysis.ipynb
```

Or view the report in the folder (REPORTS):


## Project Structure

```
global-ai-adoption/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── intermediate/
│       ├── aei_raw_claude_ai_2025-08-04_to_2025-08-11.csv
│       ├── iso_country_codes.csv
│       └── gdp_2024_country.csv
├── notebooks/
│   └── analysis.ipynb
├── figures/
│   ├── automation_vs_augmentation.png
│   └── emerging_vs_developed.png
├── outputs/
│   ├── country_automation_rates.csv
│   └── summary_statistics.csv
└── paper/
    └── Global_AI_Adoption_Patterns.pdf
```

## Data Source

[Anthropic Economic Index](https://huggingface.co/datasets/Anthropic/EconomicIndex) - September 2025 Release

Analysis covers Claude.ai usage data from August 4-11, 2025 across 200+ countries.

## Requirements

- Python 3.10+
- pandas
- numpy
- matplotlib
- jupyter

## Author

Rishi Siddharth  
American University, Data Science  
rs5309a@american.edu

## License

MIT
