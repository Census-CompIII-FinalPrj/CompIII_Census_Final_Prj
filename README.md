# CompIII_Census_Final_Prj
Comp III Fall Project AY24 - Ensign Mafia Census Group

Welcome to the OA3802 Final Project Description
This project was completed by five ensigns at the Naval Postgraduate School as part of the Computational Methods for Data Analytics Course
	
The basic workflow of this project was: <br>
	1) Gather general demographic information from 2020 Military Demographics Report PDF document (in repository)<br>
	2) Download CSV files to shared folder on class HPC drive<br>
	3) Open a tunnel to Jupyter Lab through MobaXterm<br>
	4) Read the CSV files into Pandas DataFrames<br>
	5) Use filtering, value counts, and other DataFrame methods to sort the data<br>
	6) Pull out demographics data from the CPS results and compare to Military Demographics Report<br>
	7) Use the DataFrames to answer other interesting questions about active duty service members and veterans<br>
	
Each CSV file found on the Census Bureau's website is over 100 MB in storage, and so we choose to do all of our analysis on a shared HPC folder (in a Linux environment).
Once we set this folder up, we used a series of wget statements to download the CSV files to the shared folder.
<p>
To download the material, follow these steps:<br>
	1) Go to https://www.census.gov/data/datasets/time-series/demo/cps/cps-basic.html to take a look at how the information is stored<br>
	2) To download a CSV file in the Linux environment, use the following command:<br>
		wget https://www2.census.gov/programs-surveys/cps/datasets/2023/basic/oct23pub.csv <br>
	3) To download the rest of the files, change the month and year combination in the link and repeat the wget command <br>
</p>
With all the CSV files in the shared folder, each member of the group went about doing data analysis in their own Jupyter Notebook(s).
	Note: When tunneling into Jupyter from MobaXterm, each member needed to use a different port number.

Each .ipynb file in this GitHub repository has comments that describe what the accompanying Python code does.

See the PDF entitled "Gathering Service Member Information from U.S. Census Data" for our compiled results.


