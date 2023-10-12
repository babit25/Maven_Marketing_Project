# Maven_Marketing_Project
![maven marketing](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/c5e7d12f-4c99-4841-a7a7-89168844768a)

[Image Credit](https://www.mavenmarketing.com/)


# Introduction
This is a Data analysis and visualization project of a marketing company named Maven Marketing. The project was done as part of an online assignment by Tina on Twitter(X). The project was done using Excel. 

# Skills
•	Data Cleaning

•	Excel Formula and function

•	Pivot table

•	Data Visualization and Dashboard


# The Data
The dataset contains marketing campaign data of 2,240 customers of Maven Marketing, including customer profiles, product preferences, campaign successes/failures, and channel performance. 

![Maven marketing Dataset](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/1778838d-1e06-4f09-9724-361dab91deaa)

# Business Questions
The following questions were presented to find insights from the campaign. My goal is to find answers to these questions, find insights, and provide recommendations to the team.

  a.	What factors are significantly related to the number of web purchases?

  b.	Which marketing campaign was the most successful?

  c.	What does the average customer look like?

  d.	Which products are performing best?

  e.	Which channels are underperforming?

# Data Cleaning
The dataset did not return duplicates when checked for Duplicates and a check also shows that the data types were formatted correctly.

The customer income field contains 24 Null values which may have been due to customers not imputing their income or having no current income(unemployed). I decided to treat this Null value as Customers with No income. 
Sorting the Customer Income field from highest to lowest shows an outlier I also confirmed using a chart. The outlier was replaced with the maximum value.
![Outliers Income](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/8f787f49-ac98-44e1-adc1-44fd95a89863)

# Excel formula and functions
1. The age was derived from the year of birth using the formula below

$=2023-B2$
  3 outliers were found and replaced with the maximum value
   
![Outliers Age](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/e0f8faa5-7baa-4a98-8831-498fd1da96af)

   
2.  The Marital Status field was grouped into either "couple", "single", or "others" by grouping
   
  a.  Divorced, Single, Widow, Alone as Single

  b. Married and Together as  Couple

  c. Absurd and YOLO as Others

with the formula

$=IFS(E2= "Divorced","Single",E2="Single","Single",E2="Widow","Single",E2="Alone","Single",E2="Married","Couple",E2="Together","Couple",E2="Absurd","Others",E2="YOLO","Others")$

3. The Customer Income field was grouped into four income level
   
	a. Less than 0			    - 	“No Income”

	b. 1 – 50,000 			    - 	“Low Earner”

	c. 51,000 – 100,000 		-	“Middle Earner”

	d. 101,000 and above	  -	“High Earner”

with the formula

$=IF(G2>101000,"High Earner" ,(IF(G2>51000,"Middle Earner" ,IF(G2>0,"Low Earner" ,"No Income" ))))$

# Data Analysis and Visualization
This was done using Pivot table and charts

**1.	What factors are significantly related to the number of web purchases?**
The following factors were seen to significantly affect web purchase

  a.	Level Of Education (Graduates and higher tend to make web purchases)
The level of Education affects web purchases as those who have just basic education account for just 1.2% of web purchases with 50% of the web purchases made by graduates.

![web purchase by level of education](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/76d83b66-f355-4149-9c0c-1dd1621fa272)


b.	Income (Middle salary Earners also tend to make web purchases)
Middle-income earners also made more web purchases compared to other income levels.

![web purchase by salary level](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/ba0409c9-02ff-4519-a0e4-c93a1cdf11c1)


c.	 Spain and Saudi Arabia have the highest web purchase of all the countries.

![web purchase by country](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/89dec6ce-acad-498d-b764-439eabbdb914)


d. Couples make up 65% of the total Web purchases.

![web purchase by marital status](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/f6ae791b-dbc9-438b-9f66-351dfdade7f6)


**2.	Which marketing campaign was the most successful?**

More customers responded to the 4th campaign.

![campaign](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/7c4c5330-bcd7-49b7-8e26-253603d2eb9a)


**3.	What does the average customer look like?**

The average Age, Income, Kids, and Teenagers at home were calculated which gives an idea of what the average customer looks like.

![Customer Average](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/d7770be7-1c94-45a6-a5b0-e7d8d8ec9fbb)

The average customer is 54 years old, earns $51,970 has No Kid, and 1 Teenager.

**4.	Which products are performing best?**

Wine products are the best-performing products accounting for 50.17% of the Revenue followed by meat and gold products with 27.56% and 7.27% respectively

![Products Revenue](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/3a3eebf1-1200-401d-be34-42127a37b9bd)


**5.	Which channels are underperforming?**

The bar chart was chosen to visualize the products sold via each purchase channel. The purchase via catalog was the worst-performing channel

![purchase channel](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/a0a1636d-12d8-4fe3-9499-5019eb460411)

# Dashboard
A Dashboard was created that shows all the charts and Recommendations.

![Maven Marketting Dashboard](https://github.com/babit25/Maven_Marketing_Project/assets/108529070/f92d456a-5eaa-4b4b-a530-f2d0d9c5e778)

# Insights
1.	More Educated and middle-income customers make more web purchases
2.	 4th, 3rd and 5th Campaign were the most successful. 
3.	The percentage of customers that responded to the campaigns was 30%.
4.	Best-performing products are Wines, meat, and Gold 

# RECOMMENDATIONS
1.	WEB Products should be Targeted at More Educated and middle-income Customers from Spain and Saudi Arabia.
2.	4th, 3rd, and 5th Campaigns may be repeated as they had more success. 
3.	Best-performing products such as Wines, meat, and Gold should be stocked more as they are the best-performing products.



# CONCLUSION
This project was my first real project without supervision. Your comments, contributions, and Feedback are welcome.


THANK YOU
























