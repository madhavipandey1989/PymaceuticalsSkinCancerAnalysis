# PymaceuticalsSkinCancerAnalysis
 PandasMatplotLib Module 5 Challange


Pymaceuticals Inc.
Analysis
In this analysis we were given mice data, and the treatment data set. We are to analyze the impact of drugs on tumor volume observed on mice. There were some issues with the dataset, as it had duplicate records. We identified unique records with Mouse ID and Time point as unique identifiers for the records. As the first exercise we removed the duplicate records from the dataset.

After cleaning the dataset we generated stats for Tumor Volume, calculated the data, mean, median, variance, standard deviation, SEM for each Drug Regimen. This will help us to pick the top 4 drugs with least standards deviation in the dataset for further analysis, which are Capomulin, Ramicane, Infubinol, Ceftamin.

After this, we plotted a chart for number of Observed Mouse Timepoints per drug regimen. We observed, Capomulin and Ramicane drugs had most timepoints, rest of the drugs had slightly lesser time points recorded. We also observed the distribution of sex in Mice population. 51% are male vs 49% are female mice. We learnt to plot charts using Pandas as well as Matplot lib pyplot library.

Then we looked at Quartiles and outliers, also plotted box plot. We chose the max timepoint records per mice, we chose top 4 drugs with least standard deviation in tumor volume, and ran our analysis to find outliers for each of the 4 drug regimen. We found 1 outlier for drug Infubinol. We plotted box plot for the chosen drug regimen.

Capomulin and Ramicane have lesser deviation in datasets. Capomulin looks like the best performing drug, hence chosen it for further analysis.

We chose 1 mouse which was treated with Capomulin, and plotted the line chart with Tumor volume, vs timepoint. We observed that for that mouse, the Tumor volume decreased overtime, as visible in line graph.

After that we did a scatter plot between Average Tumor volume per mice, and their weight(g). We saw that for lesser weight, the average tumor volume was observed to be less as well. To establish this correlation, we plotted correlation line on scatter plot. The correlation between mouse weight and the average tumor volume came as 0.84, which is closer to 1. establishing the correlation of mouse weight and average tumor volume for drug Capomulin. We can establish the following outcomes from this analysis.

Standard deviation calculation helped us to identify top 4 drugs for further analysis.
Capomulin turned out the best drug which helped reduce the tumor volume for mice.
We observed the correlation between mouse weigh and average tumor volume, which turned out to be closely corelated 0.84.


Files:
data/Mouse_Metadata.csv hold the mouse data
data/Study_results.csv holds the study data.
pymaceuticals_starter.ipynb  provides the detailed analysis script.
