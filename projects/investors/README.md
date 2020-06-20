# What You Can Get From Top Investors Portfolios

#### Data description:

Top investors are always very sensitive to industry information or potentials. Plus, they can access more information and have more resources to business-related materials than normal people that make their investment more precise and profitable than general investors. Thus, just by looking at the top investors' portfolios, you will find a lot of interesting insights and valuable information. 

This project is using a Python web scraper developed by Sibo to parse data from [Dataroma](https://www.dataroma.com/m/home.php), which is containing a good portion of super investors portfolio and updating regularly. It's worth noticing that the scraper is just intended to get data more efficient for personal interests for this project, it's not for any purpose involving republishing, reproducing, redistributing, or selling of the content. The data parsed is just a limited area of data provided by Dataroma. There are also other ways to get those data, the most accurate and official channel is to get data from the Securities and Exchange Commission (SEC). According to SEC, an institutional investment manager that uses the U.S. mail (or other means or instrumentality of interstate commerce) in the course of its business, and exercises investment discretion over $100 million or more in Section 13(f) securities (explained below) must report its holdings on Form 13F with the Securities and Exchange Commission (more detail from [SEC](https://www.sec.gov/fast-answers/answers-form13fhtm.html)). 

#### Data source: 
[Dataroma](https://www.dataroma.com/m/home.php) (this data is updated periodically and you will need to update data regularly in a quarterly frequency). The data used for this project is just the 2020Q1 data from the Dataroma.

***This data is just for personal interests of data visualization, please do not republish, reproduce, redistribute, or sell the content, including the data. For any detail of the Dataroma content usage, please refer to the [Dataroma terms of use](https://www.dataroma.com/m/inc/tos.php)***

#### Data workflow:
The data is scraped by a Python function developed by Sibo. This project is using Tableau as the data visualization tool calling data from local .csv files that scraped quarterly. You can find the dataflow for this project below.
<p align="center">
    <img src="./Workbook/investors_dataflow.png" alt="investors_dataflow">
</p>

#### Data insights:
- The majority of drinking water tanks are located in population-dense areas where they also have a large amount of foodservice provided to the neighborhood. Some typical places such as 33rd St., WTC, and communities around Central Park.
- The quality of the drinking water is in good condition according to the inspection results, in which only 2 tanks are not meeting the standards. Less than 0.04% of tanks show the presence of E. coli, which can cause serious food poisoning in their hosts. However, there are a large number of tanks(roughly 10,000 inspections) don't receive an inspection result, which the reason for this situation is unknown. This could be a data issue from the source or an unspecified methodology of the data being collected and gathered.
- There are around 4,500 tanks that should have been certified for each year from 2014 to 2018. We can see that certifying numbers match the expectation for 2015, 2016, and 2017, but not for 2014 and 2018.
- The certifying is largely conducted by several companies, e.g., Rosenwach Tank Co. LLC, ISSEKS BROS INC, and American Pipe & Tank. But there are many of the inspections performed by other individual companies, which might influence the efficiency of the gathering of the test results. 

#### Dashboards:

<p align="center">
    <img src="./Workbook/dashboard_1.png" alt="investors_dashboard_1">
</p>
<p align="center">
    <img src="./Workbook/dashboard_2.png" alt="investors_dashboard_2">
</p>
<p align="center">
    <img src="./Workbook/dashboard_3.png" alt="investors_dashboard_3">
</p>
<p align="center">
    <img src="./Workbook/dashboard_4.png" alt="investors_dashboard_4">
</p>