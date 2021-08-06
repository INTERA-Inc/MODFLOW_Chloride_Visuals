ReadMe Instructions for "MODFLOW_ChlorideVisuals_rev0"

1) This scripts runs on python 3+

2) Copy the script and insert into the working directory for the excel /.csv dataset

3) Open the script and set:
	i) Line 18 - directory	
	ii)Line 21 - dataset (currently set to read .csv)
	iii) Line 42, 43 - refDate and maxDate (currently set to 2003-06-01, 2021-06-01)

4) In Linux or PowerShell, set the working directory, then run the script	
	i) >>python MODFLOW_ChlorideVisuals_rev0.python
	
5) The script will take < 5mins to run; will return errors if any

6) Output:
	i) Three subfolders will be created: "ScatterPlots", "Head_Vs_Time_Figures", "Head_Vs_Time_3x2"
	