# Earthquake Risk Analyst

**Earthquake Risk Analyst** is a Python-based data science project developed as part of the *Python for Data Science* course.
The project applies statistical and analytical methods to earthquake datasets to study frequency, distribution, and regional risk factors. It demonstrates how data science techniques can be used to analyze seismic activity and identify potential high-risk zones.

This repository contains the complete project code, datasets, and documentation.     

## Objectives

* Analyze earthquake datasets to identify frequency, distribution, and trends.
* Implement data cleaning and transformation using Python.
* Visualize seismic activity using Matplotlib and Seaborn.
* Identify and estimate risk-prone geographical zones.
* Apply statistical methods for correlation and trend analysis.

## Technologies Used

| Category                | Tools/Libraries            |
| ----------------------- | -------------------------- |
| Programming Language    | Python                     |
| Data Handling           | pandas, NumPy              |
| Visualization           | Matplotlib, Seaborn        |
| Statistical Analysis    | SciPy, scikit-learn        |
| Development Environment | Jupyter Notebook / VS Code |

## Methodology

1. **Data Collection**

   * Imported global earthquake datasets containing magnitude, depth, coordinates, and timestamps.

2. **Data Cleaning and Preprocessing**

   * Handled missing values and inconsistent records.
   * Normalized numerical data.
   * Standardized date and time formats.

3. **Exploratory Data Analysis (EDA)**

   * Studied magnitude distribution and frequency.
   * Visualized spatial trends to identify risk-prone areas.
   * Examined relationships between magnitude, depth, and frequency.

4. **Modeling and Risk Estimation**

   * Applied regression and clustering for pattern recognition.
   * Conducted feature analysis to identify contributing factors.

5. **Result Visualization**

   * Generated plots of magnitude vs. frequency.
   * Created heatmaps showing geographical risk patterns.
   * Highlighted long-term seismic trends.


## Results

* Identified regions with the highest earthquake occurrence probabilities.
* Established correlations between magnitude, depth, and frequency.
* Produced clear and interpretable visualizations of risk clusters.

## Limitations

* Dataset limitations for certain regions reduced predictive accuracy.
* Model performance is dependent on data quality and sample size.
* Real-time prediction was not implemented in this version.


## Future Enhancements

* Integrate live data sources (e.g., USGS Earthquake API).
* Implement machine learning algorithms for prediction.
* Develop an interactive dashboard for real-time monitoring.

## Project Report

The comprehensive project report includes:

* Problem Statement
* Literature Review
* Data Analysis and Methodology
* Error Analysis
* Discussion and Conclusion
* References

*(Available in `report.pdf` folder.)*

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/Earthquake-Risk-Analyst.git
   cd Earthquake-Risk-Analyst
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the analysis notebook:

   ```bash
   jupyter notebook Earthquake_Risk_Analyst.ipynb
   ```

4. View the generated visualizations and analysis outputs.

## Example Output

```
Average Magnitude: 4.82  
Maximum Recorded Magnitude: 9.1  
Top 5 High-Risk Zones: Japan, Chile, Indonesia, Alaska, Turkey
```
