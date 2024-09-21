For this week's challenge,we used pandas,matplotlib,and scipy.stats to analyze 2 data sets from a pharmaceutical company that develops anti cancer medications.The data sets consists of mouse_ids,gender,age,weight of mice and drug regimens,timepoints(no. of days over which drugs were tested),tumor volume and metastatic sites.

  First we merged both data sets to have a better understanding of data.Then we dropped the duplicate enteries and generated a summary statistc table calculating mean,median,vaariance,standard deviation and standard error of mean for tumor volume for each drug.Based on this table we generated bar charts using pandas and matplotlib to show timepoints for each drug.We also calculated distribution of male and female mice and plotted it using pie charts.
  
  We selected four promising drugs and calculated final tumor volume of each mouse for these drugs and then plotted box plots and assessed IQR to determine outliers.
  Finally we generated line plots and scatter plot for the performance of company's drug of interest, Capomulin.Then we calculated correlatin coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.

