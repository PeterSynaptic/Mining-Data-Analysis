# Mining Data Analysis Dashboard

## Description
This is a Streamlit-based web application for analyzing mining data, specifically focusing on copper and molybdenum grade predictions from sensor measurements and blasthole assays. The dashboard provides interactive visualizations and statistical analysis tools for mining data exploration.

## Features
- Interactive data upload through Excel files
- Comprehensive data visualizations:
  - Grade distributions for copper and molybdenum
  - Prediction accuracy analysis comparing sensor predictions with actual blasthole assays
  - Distance vs prediction error analysis
  - Shift-wise grade analysis with temporal trends
- Summary statistics generation
- Automated report generation in Word format
- Interactive data table display
- Responsive design for different screen sizes

## Requirements
- Python 3.7+
- Required packages listed in `requirements.txt`:
  - streamlit
  - pandas
  - matplotlib
  - seaborn
  - python-docx

## Installation
1. Clone this repository:
```bash
git clone https://github.com/yourusername/mining-data-analysis.git
cd mining-data-analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage
1. Run the Streamlit application:
```bash
streamlit run app.py
```

2. Upload your Excel file containing mining data with the following required columns:
   - cugrade: Copper grade predictions
   - mograde: Molybdenum grade predictions
   - avg_bh_grade_cu: Actual copper grades from blastholes
   - avg_bh_grade_mo: Actual molybdenum grades from blastholes
   - Dist_to_NN_bh: Distance to nearest blasthole
   - shift_id: Shift identifier
   - run_date_time: Timestamp of measurements

3. Explore the generated visualizations and analysis

## Output
The dashboard generates:
- Interactive visualizations
- Statistical summaries
- Downloadable Word report containing all analysis results

## Contributing
Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.