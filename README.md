# README

# 1. Project Overview
This project aims to shed light onto the foreign population in Germany across 1967 to 2023 period. Specifically, we analyze the dataset provided by the German Federal Statistical Office, which tells about male and female foriegners per year respectively. 

After cleaning, the dataset contains 57 rows. The preprocessing was done in two steps: First, the CSV file was opened and the first few and last rows with the dataset description and error-causing symbols (not actual data) were manually removed. And the years were modified to just include the year instead of date. Since, there wasn't any missing values, there was no need of pre=processing using python.

In the data folder you will find 2 data files:
1. `Dataset`: the original dataset downloaded from the Genesis database. 
2. `cleaned_dataset`: this is a cleaned version of `Dataset`. 


# 2. Features
The project has the capability to perform some exploratory data analysis (EDA) on the dataset and answer the following 5 research questions:
1. How has the total foreign population in Germany grown between 1967 and 2023?
2. Has the gender balance among foreign residents shifted significantly during this period?
3. Are there specific years with a surge in immigration for either men or women?
4. Are there decades where one gender consistently migrated to Germany at a higher rate than the other?
5. Identifing the top 5 years with the highest total foreign population.

All questions, except 5th, are accompanied by visualizations.

# 4. License
This software is provided under the MIT license. [Click here to see the full license.](https://gitup.uni-potsdam.de/rumaney/rse/-/blob/main/LICENSE.txt)

# 5. Contact Information
Contact can be established via email: tauqeer.kasam.rumaney@uni-potsdam.de

# 6. Acknowledgements
The analysis in this project was only possible thanks to the data provided by the [Statistisches Bundesamt Deutschland](https://www-genesis.destatis.de/genesis/online?operation=abruftabelleBearbeiten&levelindex=1&levelid=1714815006034&auswahloperation=abruftabelleAuspraegungAuswaehlen&auswahlverzeichnis=ordnungsstruktur&auswahlziel=werteabruf&code=12521-0001&auswahltext=&nummer=4&variable=4&name=GES&werteabruf=Value+retrieval#abreadcrumb).