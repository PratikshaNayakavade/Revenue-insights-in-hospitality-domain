# Revenue-insights-in-hospitality-domain
Provide Insights to the revenue team in the hospitality domain.

**Task**:  

AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Data analyst who has been provided with sample data and a mock-up dashboard to work on the following task. You can download all relevant documents from the download section.

Create the metrics according to the metric list.
Create a dashboard according to the mock-up provided by stakeholders.
Create relevant insights that are not provided in the metric list/mock-up dashboard.


-----------------------------> Data Loading and Power Query Documentation -------------------------------------->


1. Create a folder in Desktop and store all the csv files related to hospitality challenge.

2. Open a Power BI file, and In "Get Data", select the option as folder and browse through the folder containing csv files.

3. Then go to Tranform data to expand each and every dataset.

4. Now, duplicate the data source 4 times and in each one, expand one dataset by clicking on "Binary" option. also, rename 
   the tables accordingly.

*****************  Power Query steps for tables:  *******************
1. dim_date:
	- remove the column 'day_type'
	- we are deleting this because, we got a feedback from the mock dashboard review that Friday and Saturday are           
	  considered as weekends in the industry and not sunday. But In our datasets, saturday and sunday are considered           
	  as weekends. So we delete this column and re-create day_type using calculated columns.

2. dim_rooms
	- The column names are not captured here. We need to select "Use First Row as Headers" option .
