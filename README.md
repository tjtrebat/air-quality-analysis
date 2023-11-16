# air-quality-analysis
# Introduction
This Python script performs statistical analysis on the Houston Air Quality Index (AQI) dataset. The analysis includes hypothesis testing and comparison of selected variables.
# Part 1: Hypothesis Testing for 'avg_pressure'
# Load the data
Randomly select 100 samples from the 'avg_pressure' column.
Set up hypotheses for mean and proportion testing.
Conduct a one-tailed t-test for the mean and a binomial test for the proportion.
Calculate a 95% confidence interval for the mean.
Print and visualize the results using histograms.
# Part 2: Comparison with Other Variables
Randomly select 100 samples from 'avg_wind', 'avg_temperature', 'avg_humidity', and 'avg_pressure'.
Compare the means and standard deviations of 'avg_wind', 'avg_temperature', and 'avg_humidity' with 'avg_pressure'.
Perform t-tests for each variable pair.
Calculate standard deviations and 95% confidence intervals.
Print and visualize the results using boxplots.
# Dependencies
Pandas
NumPy
SciPy
Matplotlib
Seaborn (for boxplots)
# Instructions
Ensure you have the required dependencies installed (pip install pandas numpy scipy matplotlib seaborn).
load csv
Update the file_path variable in the script with the correct file path.
Run the script to perform the analysis.
