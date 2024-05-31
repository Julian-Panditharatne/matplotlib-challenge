# Matplotlib Challenge

This challenge involves analyzing the data and writing a top-level summary of the results from an animal study data in which 249 mice that had SCC tumors received treatment with a range of drug regimens and the tumor development then oberved and measured over the course of 45 days, for the purpose of comparing the performance of one of the drugs, Capomulin, against the other treatment regimens. The analysis was conducted in the following manner.

- After cleaning the data by removing data of any mice with duplicate time points, the tumor measurements were aggregated for each drug regimen using the following statistics: mean, median, variance, standard deviation, and standard error of the mean (i.e., SEM) of the tumor volume.
- The amount of measurements, i.e., rows in the dataframe, was also aggragated for each drug regimen throughout the study, and displayed using barcharts. The distribution of female versus male mice in the study was calculated and displayed in pie charts.
- The interquartile ranges (i.e., IQR) were calculated and potential outliers were found and displayed for the distributions of the final tumor volumes of each mouse across the four most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin; and they were also showcased in a boxplot.
- A line plot of tumor volume versus time point for a single mouse that was treated with Capomulin was generated.
- The correlation coefficient and a linear regression model was calculated for mouse weight and average observed tumor volume for the entire Capomulin treatment regimen and displayed in a scatter plot.

---

## Repository Files and Folders

Besides this README file, there are 9 other files and two folders:

The folder, which is named *Pymaceuticals* contains 7 of the other files and the other folder named *data*

- **pymaceuticals_starter.ipynb**: The jupyter notebook file containing the starter code used in the main script file, **pymaceuticals.ipynb**.
- **pymaceuticals.ipynb**: The jupyter notebook file containing the written analysis and the script run to analyze the mice and study data in **Mouse_metadata.csv** and **Study_results.csv**.
- **image-1.png**, **image-2.png**, **image-3.png**, **image-4.png**, **image-5.png**: Charts and plots included in the written analysis.

The *data* folder contains the other 2 files:

- **Mouse_metadata.csv**: dataset containing information on each mice
- **Study_results.csv**: dataset containing information gathered from the study.

---

## References

*API reference — pandas 1.4.2 documentation.* (2024, April 10). Pandas Documentation. <https://pandas.pydata.org/pandas-docs/stable/reference/index.html#api>

Hunter, J., Dale, D., Firing, E., Droettboom, M., & Matplotlib development team. (n.d.-a). *API reference.* Matplotlib.org. Retrieved May 2024, from <https://matplotlib.org/devdocs/api/index.html>

Hunter, J., Dale, D., Firing, E., Droettboom, M., & Matplotlib development team. (n.d.-b). *Examples.* Matplotlib.org. Retrieved May 2024, from <https://matplotlib.org/stable/gallery/index.html>

The SciPy community. (2019). *Statistical functions (scipy.stats) — SciPy v1.3.3 reference guide.* Scipy.org. <https://docs.scipy.org/doc/scipy/reference/stats.html>

*User Guide — pandas 2.1.1 documentation.* (2024, April 10). Pandas Documentation. <https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide>