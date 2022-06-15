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

<code><img height="600" src="https://user-images.githubusercontent.com/106002818/171074104-8ce01bd5-7dea-4606-87ab-3d6a0919a150.png"></code>

With this very simple query I was able to compare some preliminary results for percentage of unvaccinated children and the impact on infant mortality. Initially, infant mortality was given as "per 1,000 individuals". To keep the data consistent, I divided these numbers by 1,000 to get the percentage infant mortality to compare to the percentage of unvaccinated infants. I also formatted the percentages to make the report a little more readable. 

Okay, I'll be honest. I'm meeting a little roadblock at this part of the project and because this is a project writeup, I thought it would be good to share. Here are the issues I'm having right now:

1. I had this idea that I wanted to answer a different set of data science questions on a different table for each different language I want to use in this project. This way, I find new and interesting insights without repeating the same exercises and I get to practice or showcase those languages on Github. What I failed to realize in my enthusiasm, however, is that the questions I picked for this particular part of the project would be better suited to a different language or analytical tool. I may go forward by changing the questions so I can give SQL a chance to really shine in this analysis, or build the database in SQL to show that I can then move to another language such as R or Python for the analysis. I'm leaning towards option A, maybe I'll do some queries using joins? I need to stew on that for a little longer. My first action item for this phase of the project: "Refine questions to use SQL-specific features or redefine the goals of this portion of the project". 

2. Microsoft Access is not giving me the IDE features I really want for this project. I'm glad I started in Access because I got some experience with importing data from Excel, cleaning data in Access, and using different features. But I find that, because I haven't built the database from scratch, it doesn't quite have the custom feeling that I'm looking for. I don't feel that I'm getting as much practice as I would like with the actual coding portion of this project. Also, I've had to put my SQL code on Github as a txt file, which doesn't register as SQL code when Github assesses my "languages used". As a data person, this drives me nuts! I want my lines written per language percentages to be accurate on Github, especially when I'm working here so people can see what my skills are. Because of all of this, I have installed Oracle SQL Developer and hope to use it for the rest of this project. Here I get to my second action item, "Learn how to synch Oracle SQL Developer with Github". I hope it's as easy as R!

3. Lastly, I need to get my excel database converted into a series of insert statements or read the file directly to create a new SQL database. I attempted this at the very beginning of the project using a JSON file, but then my mentor and I worked to clean the data in Excel instead and import it into Access directly. I could write a huge INSERT statement with every entity accounted for. Because I'm trying to learn by doing with this project, I'm looking for a more efficient solution. In the real world, I would hate to bill my company for a few hours of me repetitively typing data entries when a more efficient solution exists. My last action item for this phase of the project is: "Find a way to import a database from Excel to Oracle SQL Developer efficiently and effectively". 

This is why I love project-based learning! These problems I run into can be frustrating at first, but learning to solve them is so empowering. Project-based learning brings me to a point where I could actually teach someone how to work through a problem I encountered, bringing me to a much deeper level of understanding than tutorial-based learning or repetitive exercises. Yes, it can be annoying to solve one problem and have three more pop up. But the victory is so much sweeter when it's hard-won! 
