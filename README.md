#### *Capstone Project: August 2023*

![ezgif com-video-to-gif (1)](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/f79c85bb-6979-42a1-9d92-913704695272)


# Sales Performance Review

Capstone project output from "SP503 Storytelling Using Data" facilitated by Project SPARTA from Development Academy of the Philippines. The course aims to teach us about data storytelling and its elements, improve our presentation skills by explaining content, structure, packaging, and human elements, and guide us in learning strategies and techniques to engage our audience effectively through data storytelling.

## Activity

![Activity](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/77ffcec0-dc44-4e53-ad18-2bfb359703bd)

## Dataset Context

I used data from a food industry company, which includes various Excel files as follows:

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/3d134715-59fc-4f42-80eb-017f93706a36)

- The first dataset contains invoice details with columns: "Order ID," "Date," "Meal ID," "Company ID," "Date of Meal," "Participants," "Meal Price," and "Type of Meal."
- The second dataset, named "Order Leads," consists of columns such as "Order ID," "Company ID," "Company Name," "Date," "Order Value," and "Converted."
- The third dataset, named "Sales Team," comprises columns like "Sales Rep," "Sales Rep ID," "Company Name," and "Company ID."

These datasets will be utilized to assess sales performance by year, segment customers, and categorize sales team members based on performance, distinguishing between top and bottom performers.

## Criteria

![Criteria](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/09263cb6-ac4b-4f09-8ca0-19ae9f7df179)


## Peer Assessment

![SP503 1](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/4a3cedf4-879d-4878-9899-93f3ad8ff769)

![SP503 2](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/659d3a41-43f2-4918-81af-d765e72f97e4)

![SP503 3](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/6cce3827-33ac-4857-88ba-bf34dca79612)

![SP503 4](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/7e6d3b25-a397-4649-b27a-1ee5b5a2589b)

![5](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/c37fccdd-be24-45c2-9b94-300e7f20e7a8)


## Overall Peer Grade Assessment

![Grade](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/0dd6dffc-c802-4bf2-b99d-abc30be3acf0)

---
## Methodology
The sales performance analysis was carried out by creating pivot tables and measuring columns in the following steps:
- A pivot table was generated from OrderLeands.xlsx, featuring columns: "Year," "Not Converted," and "Count of Company Id."
- This pivot table data was then used to create another table containing columns: "Year," "Not Converted," "Count of Company Id," "Converted," "Conversion Rate," and "YTY." The "Converted" column was calculated by subtracting the "Count of Company Id" from the "Not Converted" values.
- To calculate the conversion rate, we compared the converted values of the current year with the previous year, minus 1, to ascertain the percentage increase or decrease. The "YTY" column represents the yearly change in the conversion rate.


For RFM Segmentation, the process included creating multiple pivot tables and interconnecting them using "index-match syntax" in the following manner:
- Generated a pivot table from Invoices.xlsx containing "Company ID, Count of Order Id, Max of Order Date, Average of Meal Price," in a new tab for RFM Segmentation Analysis.
- We then added a Sales Representative Column beside the RFM segmentation column by using "index-match" to refer to SalesTeam.xlsx, matching each customer with their assigned sales rep for further sales analysis.
- From the pivot table made using 'index-match' for sales reps, we made a new pivot table to help us sort sales reps by 'Sales Rep Name,' 'At Risk/Need Attrition,' 'Immediate Attention,' 'Loyal Customers,' 'Top Customers,' and 'Grand Total' to analyze their performance.
- By utilizing the newly extracted pivot table, we conduct Sales Representative Segmentation to identifying top and bottom performers based on this information.

This structured methodology enables detailed examination of sales metrics and effective segmentation of sales representatives to pinpoint top and underperforming individuals.


## Visualization:

The process continued by visualizing the data using various charts to present insights:

- Line Chart: Depicting continuous sales growth from 2018 to 2022.

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/35583bee-c1bd-4cd4-912a-e70c18df5112)

- Another Line Chart: Illustrating the trend in conversion rate growth across these years.

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/5f6d04ba-6d95-4287-9dbd-7d2e7e810694)

- Pie Chart: Representing customer value segmentation, categorizing customers into top, loyal, at risk, and needing immediate attention.

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/8353d817-2570-4cf7-a0e0-fa3a35927c33)

- Another Pie Chart: Showcasing Sales Representative Value Segmentation as "Outstanding Performers, High Performers, Average Performers, At Risk/Need Improvement, and Immediate Attention."

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/6c6ce2e8-a732-4901-bcd9-b0b645ab086e)


These visualizations are intended to offer insights into the sales trends, customer value distribution, and the performance categorization of sales representatives.


## Results and Discussion

### Sales Growth Over the Years

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/64b44a16-5090-420a-bee8-05414a83263d)

The sales recovery growth from 2021 to 2022 was 1.23%, resulting in an increase of ₱49,532.00. Over the broader period, from 2018 to 2022, the average yearly sales growth was 0.70%, depicting an additional ₱28,220 of sales increase annually.

### Conversion Rate Over the Years

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/4d670707-f875-4f35-abd2-ff0cafeebe28)


So, the conversion rate from 2018 to 2022 stood at 9.46%, resulting in an increase of 1,529 total orders since inception. The average conversion growth rate during this period was 2.07%, depicting an additional 334 orders per year on average.

### Customer Value Segmentation

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/feffbb5e-6e18-4744-8428-91e3184d978c)


The top customer segment, constituting 17% of the total customer value segmentation, showcases higher average monetary value (₱450.90) and frequency (14 orders), with the latest purchase recorded on December 31, 2022.

Contrastingly, the immediate attention segment, occupying 21% of the total customer value segmentation, portrays a lower monetary average (₱338.95) and frequency (8 orders), with the latest purchase recorded on December 13, 2022, indicating potential areas needing prompt attention or improvement.

### Sales Representative Value Segmentation

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/dcb9649d-bfac-470e-bd66-161b29043b0a)


The outstanding sales representative segment, comprising 8% of the total sales representative segmentation pie chart, embodies exceptional attributes:

- "Need Attrition" Accounts: 2
- "Need Attention" Accounts: 2
- "At Risk" Accounts: 2
- "Loyal" Accounts: 6
- "Top" Accounts: 3


Meanwhile, the immediate attention sales representative segment portrays concerning aspects:

- "Need Attention" Accounts: 3
- "At Risk" Accounts: 5
- "Loyal" Accounts: 3
- "Top" Accounts: 2

This segment indicates a higher count of accounts needing attention and at risk, reflecting potential challenges or issues requiring immediate resolution or improvement.


---
### *Overall, this project provided a comprehensive framework for analyzing QR code marketing data, empowering users to glean actionable insights, make informed decisions, and refine marketing strategies.*

![image](https://github.com/jvenncpe/Sales-Performance-Review/assets/35190918/1a3cc5c5-af01-4261-a652-4e1fc1b92375)

Youtube Link for the full run of the story telling:

https://youtu.be/G5EHkQ5p3M8

# Thank you!
