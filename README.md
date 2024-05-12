# Telecom-Analysis-Power-BI 
Power BI Report for analyzing Impact of 5G on AtliQ telecom company business.
Delighted and glad to present my Power BI project Telecom Domain which is a part of Codebasics Resume Project Challenge 3

# 📊𝗣𝗿𝗼𝗯𝗹𝗲𝗺 𝗦𝘁𝗮𝘁𝗲𝗺𝗲𝗻𝘁
AtliQo Telecom is a major telecom player that provides telecom services across India. Currently the company has introduced 5G and thus want to compare their performance before and after implementation of 5G. The Management has outsourced the task for data analysis to ensure they undertake calculated data driven decisions. 


 ## 𝗞𝗲𝘆 𝗠𝗲𝘁𝗿𝗶𝗰𝘀 presented in the Dashboard:-
💰 Total Revenue

💸 Avg. Revenue 

👤 Average Revenue Per User (ARPU)

👥 Total Active Users 

❌ Total Unsubscribed Users

🔍 Market Share %

💶 Revenue Before 5G

💵 Revenue After 5G

📈 ARPU Before 5G

📉 ARPU After 5G

🗣️ Active Users Before 5G

👥 Active Users After 5G

🌐 Unsubscribed users Before 5G

✨ Unsubscribed users After 5G



# The Power BI report contains 6 tables (3 Dimension and 3 Fact) imported to power BI orignaly available in CSV file:
1. dim_cities
2. dim_date
3. dim_plan
4. fact_atliqo_metrics
5. fact_market_share
6. fact_plan_revenue



# Column Description for dim_cities:
1. city_code: This column represents the unique code given for each city.
2. city_name: This column represents the name of the city corresponding to the city code.



# Column Description for dim_date:
1. date: This column represents the starting date of each month. 
2. month_name: This column represents the month names in abbreviated form(Example: Jan, Feb, Mar, etc). We have months starting from January to September except for May.
3. before/after_5g: This column represents the unique category based on the month. We have 2 categories, Before 5G and After 5G. January to April comes represents the period before 5G implementation and June to September represents periods after 5G implementation.
4. time_period: This column represents the unique sequence number ranging from 1 to 4. These time Periods are used to make respective months comparisons before and after 5G implementation (Example: Jan vs Jun, Feb vs Jul, Mar vs Aug and Apr vs Sep)




# Column Description for dim_plan:
1. plan: This column represents the various internet plans provided by the Atliqo company to the users. 
2. plan_description: This column represents the brief description about the internet plan.



# Column Description for fact_atliqo_metrics:
1. date: This column represents the starting date of each month.
2. city_code: This column represents the unique pincode code given for each city.
3. company: This column represents the company name for which the data is provided. In this dataset it's only Atliqo. 
4. atliqo_revenue_crores: This column represents the revenue that Atliqo got on that particular month in that city_code in crores(unit of currency in India - 1Crore = 10 Million) from the internet users. 
5. arpu: This column represents the average revenue per user. That means on average how much revenue Atliqo generated on single user for a given time period.
6. active_users_lakhs: This column represents the number of active users who are using Atliqo's service on that particular month in that city_code in lakhs(unit of currency in India - 1 Lakh = 100,000).
7. unsubscribed_users_lakhs: This column represents the number of unsubscribed users who unsubscribed from Atliqo on that particular month in that city_code in lakhs(unit of currency in India - 1 Lakh = 100,000). 




# Column Description for fact_market_share:
1. date: This column represents the starting date of each month.
2. city_code: This column represents the unique code given for each city.
3. tmv_city_crores: This column represents the total market value of the city in that month in crores(unit of currency in India) from the internet users. 
4. company: This column represents the different competitor names in the telecom industry [Atliqo, Britel, DADAFONE, PIO, Others].
5. ms_pct: This column represents the percentage of market share gained by respective company from the total market value(tmv_city) on that particular month in that city-code. 




# Column Description for fact_plan_revenue:
1. date: This column represents the starting date of each month.
2. city_code: This column represents the unique code given for each city.
3. plans: This column represents the various internet plans provided by the Atliqo company to the users.
4. plan_revenue_crores: This column represents the revenue that Atliqo got from that respective plan on that particular month in that city_code in crores (unit of currency in India - 1Crore = 10 Million).



# 🔗 𝗟𝗶𝗻𝗸𝘀:- 

Video Presentation Link:-

Live Dashboard Link:-

Portfolio Website link:-


# 💡𝗞𝗲𝘆 𝗟𝗲𝗮𝗿𝗻𝗶𝗻𝗴𝘀 :-

1.  𝗠𝗮𝘅 𝗥𝗲𝘃𝗲𝗻𝘂𝗲 Comes from 𝗠𝘂𝗺𝗯𝗮𝗶 and Min revenue comes from 𝗥𝗮𝗶𝗽𝘂𝗿 city before and after implementation of 5G.
2. 𝗠𝗮𝘅 𝗔𝗥𝗣𝗨 comes from 𝗟𝘂𝗰𝗸𝗻𝗼𝘄 before 5G and Max ARPU comes from 𝗣𝗮𝘁𝗻𝗮 after 5G.
3. 𝗠𝗮𝘅 𝘂𝗻𝘀𝘂𝗯 𝘂𝘀𝗲𝗿𝘀 before 5G comes from 𝗠𝘂𝗺𝗯𝗮𝗶 and Max unsub users after 5G comes from 𝗗𝗲𝗹𝗵𝗶.
4. 𝗣𝗜𝗢 is the leading Telecom Competitor and holding maximum Market Share %, Atliqo comes third in Market share % acquired by leading Telecom Players.

# 👇𝗖𝗼𝗻𝗰𝗲𝗽𝘁𝘀 𝗮𝗽𝗽𝗹𝗶𝗲𝗱:

⏺Data Modelling

⏺Data Transformation in Power Query

⏺Calculated columns

⏺DAX measures

⏺Bookmarks to switch between visuals

⏺Dynamic titles

⏺Deploying the solution to Power BI services

⏺Personal gateway to set up auto-refresh of data


# 🪛𝗧𝗼𝗼𝗹𝘀 𝘂𝘀𝗲𝗱 :-

🔨 Microsoft Power BI Desktop and Power BI Service.

🔨 MySQL Workbench

🔨 DAX Language

🔨 Power Query

🔨 M language

🔨 Microsoft Excel Power Pivot 

🔨 DAX Studio
