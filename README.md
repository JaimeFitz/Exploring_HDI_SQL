# Exploring_HDI_SQL
 An exploration of the United Nations Human Development Index using SQL

To view my first table analysis, done in R, check out my Exploring_HDI_R repository! In my second table analysis for the Human Development Index database, I will be analyzing the Health Outcomes table. This table includes information on various diseases and health challenges and their prevalence in different countries. The table includes fields for child malnutrition, malaria, mortality rates, and HIV, among others. 

My first step included cleaning the data and eliminating countries with missing data. This is crucial to note, some of my findings may be skewed because some developing countries did not provide results. After this step was completed, I imported the Excel tables in Microsoft Access. 

I used the query design feature in Access to gain access to SQL view for the data. From there, I was ready to write my own queries from scratch. 

In my analysis of this table, I will seek to answer the following questions:

1.) Is there a correlation between infants lacking DTV and measles vaccine and infant mortality?

2.) Is there a correlation between overall health expenditure as a percentage of GDP and life expectancies?

3.) Is mortality from noncommunicable diseases higher for females or males? Does this change when we group countries by over human index ranking? (Group A: HDI 1-100, Group B: HDI 101 - 196) 

4.) Is the percentage of infants exclusively breastfed correlated with adult female mortality?

For the first question, I used the SQL viewer within Microsoft Access to create this report 

<code><img height="150" src=""></code>
<code><img height="400" src=""></code>

With this very simple query I was able to compare some preliminary results for percentage of unvaccinated children and the impact on infant mortality. Initially, infant mortality was given as "per 1,000 individuals". To keep the data consistent, I divided these numbers by 1,000 to get the percentage infant mortality to compare to the percentage of unvaccinated infants. I also formatted the percentages to make the report a little more readable. 
