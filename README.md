Performance Analysis of Players in T20 Men's Cricket World Cup 2022

Created a Power BI Dashboard which helps to review and compare performances of all the players in tournament. The dashboard also enables us to select best eleven of the tournament based on their performance based on some selection criteria
Intereactive Dashboard : https://app.powerbi.com/reportEmbed?reportId=aa3c7b75-f208-4f79-9058-8b15f34058b7&autoAuth=true&ctid=a84592b2-fdaf-489f-bec3-37c7f6064a61

Steps:
•	Data Collection:   Scrapped all the data regarding match and world cup from www.espncricinfo.com and all details about players career from cricbuzz.com using Beautifull Soup library of Python.
	
•	Data Transformation:   Performed initial data cleaning after scrapping such as player name correction, match id linking etc. using Pandas. Then, transformed the final data for dashboard using Power Query of PowerBI

•	Data Modelling:   Connected all the datasets with based on some defined primary keys sucha s team and match ids. Also, created many measures, calculated columns and parameters for data analysis and dashboarding using DAX.

•	Dashboarding : Craeted final dashboard using Power BI visuals.


Tools used:
•	Python -> Beautiful Soup, Pandas
•	Power BI -> Power Query, DAX
•	Jupyter -> Data Cleaning 

