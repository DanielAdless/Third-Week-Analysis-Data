## Third Week Analysis Data

**Social Aid Distribution Monitoring**

This dataset is data on the COVID-19 Social Assistance program distributed by the DKI Jakarta Provincial Government (Pemprov) and the Ministry of Social Restrictions of the Republic of Indonesia (Kemensos RI) to vulnerable families affected by COVID-19 during the Large-Scale Social Restriction (PSBB) period in Jakarta.




**Data Understanding**

•	Social Aid Distribution Monitoring Data to vulnerable families affected by COVID-19 in Jakarta during the PSBB period

•	This dataset is sourced from data.jakarta.go.id
https://data.jakarta.go.id/visualisasi/detail/188

•	The dataset has 9 columns and 2693 rows




**Data Dictionary**

•	No: Sequence number or unique identifier for each entry in the dataset.

•	City Area: is a city area or area in DKI Jakarta where the COVID-19 Social Assistance program is implemented.

•	Subdistrict: Indicates the subdistrict within the city area where assistance is distributed.

•	Kelurahan: Kelurahan is a smaller administrative unit than kecamatan.

•	RW (Citizens' Rukun): is a smaller administrative unit in the subdistrict.

•	The recipient (KK): is the number of family heads (KK) who receive social assistance in a given location

•	Distribution Schedule: is a schedule that governs when the distribution of social assistance will be performed at a particular location

•	Distribution Date: Distribution date refers to the specific date when social assistance is distributed

•	Cost: This column may contain information about the types of basic materials distributed to recipients






**Data Preparation:**

• Code Used

• Python Version 3.11.4

• Packages Pandas, Numpy, Matplotlib, Seaborn




**Data Cleansing**

• Purging Data because there are two columns that do not match the data type, namely the distribution schedule column and the distribution date

•Replace missing values with mean values





**Exploration Data Analysis**

•	Visualization of the number of Top 5 aid recipients (KK) based on District

•	Visualization of the highest and lowest number of recipients (KK) based on City Region

•	Visualization of the lowest number of aid recipients (KK) based on RW

•	Visualization of the lowest percentage of five recipients (kk) by kecamatan

•	Percentage visualization of the food type distribution














**💡📈 Three full weeks of challenges and knowledge on the way as an analyst data scientist. As we enter the third week, we deepen in data analysis, dig up valuable insights, and continue to pursue change📊**
