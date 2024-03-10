# Canada_GHG_Emission
The purpose of this project is to analyze and understand greenhouse gas (GHG) emissions in Canada over the past five years, focusing on various sectors contributing to these emissions. With a primary emphasis on carbon dioxide (CO2) emissions, the project aims to identify and evaluate which sectors have been the most significant contributors to Canada's overall GHG emissions.

The project aims to provide insights into key contributors to Canada's overall GHG emissions, facilitating informed decision-making regarding emission reduction strategies.

## System Overview:- Data Sourcing

                     	https://open.canada.ca/data/en/dataset/ad009bb9-118d-49ce-a57a-f7b79e3e032f

                          https://open.canada.ca/data/en/dataset/6bed41cd-9816-4912-a2b8-b0b224909396

 **Data Storage**	In the data storage section for your project, you can mention that the data files containing greenhouse gas emissions data for Canada were directly loaded into Tableau for analysis and visualization. Since no traditional database was utilized, the data files themselves served as the primary source of information for the project.
 
**ETL Process**	I loaded the files and attempted to eliminate any null values. After checking for the correct data types and errors, I normalized the data and loaded it into Tableau to create the visuals.

**DATA Modelling**	I established a star schema linking the fact table with six other tables.

**Visualization**	Initially, I crafted distinct and insightful charts intended for display on the dashboard. Next, I devised relevant measures to support my dashboard. Finally, I opted for specific chart types to enrich the visualization of the dashboard.

## Data Management 

It includes tables:
•	Agriculture
•	Electricity
•	Intensity
•	Nationals
•	Regional
•	Sector
•	Transport

**ETL Process:**

Extract: 
Taken Data from open Canada which incudes tables which I have mentioned above.Each table provides analysis of CO2 emission from different sectors.

Transform: 
Cleaned and Changes data set for better structured and organized format.
Unpivoted columns and unified them in one column.
Removed null/void values.

Load:
Loaded the transformed data into Tableau for analysis and visualization.
Created data models and Relationships.




## Data Modelling

**Entity-Relationship Diagram**


![image](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/8464ea1e-2993-486a-a2ab-c88b3859ea1d)

 



**Tables and Fields:**

	National:- Contains fields Year and Total Green house Gas Emission 

	Regional:- Province, 1990 GHG data, 2005 GHG data, 2020 GHG data

	Sector:- Year, Oil and Gas, Transport, Buildings, Electricity, Heavy industry, Agriculture, Waste and others.

	Transport:- Year, Passenger Cars, Passenger Light Trucks, Passenger Motorcycle bus Rail aviation, Freight Heavy duty trucks, Freight Rail Aviation Marine, Other

	Intensity:- Year, GHG emission per person, Indexed GHG emission per person, GHG emission per GDP, Indexed GHG emission per GDP

	Electricity:- Year, Coal, Natural Gas, Other

	Agriculture:- Year, On farm Fuel Use, Crop Production, Animal Production

**Schema Design**

![image](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/23090b05-18f5-4c73-a6b1-f8b5918ebb87)

![image](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/89639306-c821-41ef-bd5c-da94abf21d9a)

![image](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/a2d024b5-7b8b-4387-82c5-27cd502ff5e9)

![image](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/c5ec0a69-575f-4817-9bdc-5f90f10c8490)

![image](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/04ab32a6-a52d-474b-9853-5c9299d7a645)

![image](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/91b30e8b-9d9c-4acd-90cd-bbd0e2b9b0e9)








**Visualization & User Interface**

Layout

1st Dashboard :- The initial dashboard exhibits greenhouse gas emissions across various sectors, highlighting the transport sector as the primary emitter of CO2. Additionally, it presents GHG emissions by the electricity sector, along with factors contributing to CO2 emissions.

![Screenshot 2024-03-03 215439](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/6c80f1c1-1789-436b-a21b-e00fbb9eff75)


2nd Dashboard:- The second dashboard showcases a map chart depicting GHG emissions by region, highlighting Alberta as the province with the highest increase in CO2 emissions.

![Screenshot 2024-03-03 215504](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/d7cde3aa-a824-4c69-9aaf-21b20dbf7ba9)


3rd Dashboard:- The final dashboard illustrates alternative energy sources utilized across provinces and the various sources employed for energy generation throughout all provinces.

![Screenshot 2024-03-03 215514](https://github.com/Kanika300393/Canada_GHG_Emission/assets/145607662/59fe2e41-c04c-4c85-8181-364e17a4b260)


**Features & Functionalities**

o	The user interface will offer fundamental functionalities for navigating between different dashboards. Yearly filters can be applied using slicers. All key performance indicators (KPIs) are listed at the top of the dashboard for easy reference

**Technical Requirements**

Software & Tools

Tableau:- Tableau is a data visualization software that helps users turn complex data into interactive and insightful visualizations. It allows users to connect to various data sources, create dynamic visualizations, and share insights across teams and organizations.

Microsoft Power BI: Power BI is a business analytics tool that provides interactive visualizations and business intelligence capabilities. It allows users to connect to various data sources, create dynamic reports and dashboards, and share insights across the organization.

**Conclusion**

Goals from the dataset would be:

	What sector is the largest contributor to greenhouse gas emissions?

	What strategies can be adopted to stabilize or decrease emissions originating from the electricity sector?

	Which province exhibits continual growth in greenhouse gas emissions?

	Examine greenhouse gas emissions across various sectors and analyze greenhouse gas emissions by province



















