# Power-BI-Capstone-project
## Steps
* Prepare its sales data.

* Configure its data sources.
  configured the data sources by adding sales data, ensuring the accuracy of the data types, and transforming the historical currency exchange data. 

* Design and develop a data model.
  designed and developed a data model using the tables created in the previous scenario. A well-designed data model is the most effective way to visualize data and its relationships.
  As part of the data model’s design and development, configured the model’s relationships, defined a calendar table, and used DAX to calculate sales and profit metrics.
  - data model’s tables should be configured as follows:

    - A one-to-one relationship between the Countries and Exchange Data tables based on the Exchange ID field.

    - A many-to-one relationship between the Sales and Countries tables based on the Country ID field.

    - A one-to-one relationship between the Purchases and Sales tables based on the OrderID field.

    - A many-to-one relationship between the Calendar and Purchases table based on the Date field.

    - A many-to-one relationship between the Sales in USD and Sales tables based on the OrderID field.

    - In all instances, the cross-filter direction of each relationship should be set to Both.
* Created time-based summaries for displaying quarterly, annual, and year-to-date profit data.

* Determined median sales volume to assess Tailwind Traders' performance stability.

* Utilized the *Performance Analyzer* tool to enhance report generation and ensure fast loading times.

