### Table of Contents

- [Data Source](#data-source)
- [Key Questions Explored](#key-questions-explored)
- [Data Preprocessing](#data-preprocessing)
- [Data Analysis](#data-analysis)
  - [Sales Trends Over Time](#sales-trends-over-time)
  - [Product Performance Assessment](#product-performance-assessment)
  - [Top-Selling Products by Quantity](#top-selling-products-by-quantity)
  - [Geographical Sales Distribution](#geographical-sales-distribution)
  - [Top 5 Cities with Highest Order Volumes](#top-5-cities-with-highest-order-volumes)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Appendix](#appendix)



# Sales Performance Analysis of an Electronic Company

### Introducton
This Power BI dashboard offers comprehensive insights into the sales performance of an electronics company, facilitating a nuanced understanding of key metrics and trends. Leveraging interactive visualizations enables the exploration of sales data across different periods, product performance, revenue distribution, geographical patterns, and growth opportunities.

### Data Source

The dataset utilized for this project was acquired from [Kaggle](https://www.kaggle.com/datasets/dhruvkothari19/practice-eda-on-this-sales-dataset/download?datasetVersionNumber=1), encompassing 12 months of Electronics store data. It comprises crucial variables such as Order IDs, Products, Quantities Ordered, Prices, Order Dates, and Purchase Addresses.

### Key Questions Explored

This project aims to address pivotal questions, including:

- What are the noticeable sales trends across various periods?
- Which products demonstrate robust performance, and which exhibit room for improvement?
- What are the top-selling products by quantity?
- What is the geographic breakdown of sales distribution?
- Which cities account for the highest order volumes?

### Data Preprocessing

Before analysis, the dataset underwent meticulous preprocessing steps, ensuring data integrity and relevance. Key preprocessing steps included:

- Data Cleaning: Elimination of duplicates, handling missing values, and rectifying inconsistencies within the dataset.
- Data Transformation: Standardization of data formats and units of measurement to facilitate seamless comparison.
- Feature Engineering: Development of new measures such as 'Total Revenue' and 'Total Quantity' to enhance analytical depth.

### Data Analysis

#### Sales Trends Over Time

Dynamic time-series charts within the dashboard unveil a consistent uptrend in sales throughout the year, with a significant spike during the holiday season. These insights underscore the imperative of maintaining optimal inventory levels during peak sales periods to mitigate stockouts and capitalize on revenue opportunities.

#### Product Performance Assessment

Visual depictions, particularly bar graphs, highlight the exceptional sales performance of specific product categories like Laptops and Smartphones in terms of both sales volume and value. This insight acts as a fundamental basis for well-informed inventory control and focused marketing efforts, guaranteeing the effective promotion and accessibility of sought-after products.

#### Top-Selling Products by Quantity

The donut chart highlights the top three products in terms of sales quantity, prominently featuring Smartphones, Laptops, and Monitors. This insight informs strategic decision-making on inventory replenishment and resource allocation.

#### Geographical Sales Distribution

Geospatial visualizations underscore sales dispersion across different regions, with notable concentrations observed in the country's western, southern, and eastern parts of the United States. Conversely, sales in areas such as Maine (ME) appear comparatively subdued. This geographic insight informs tailored marketing campaigns and inventory optimization efforts in alignment with regional demand dynamics.

#### Top 5 Cities with Highest Order Volumes

The dashboard concisely pinpoints the top five cities contributing to the highest order volumes, comprising San Francisco, Los Angeles, New York City, Boston, and Atlanta. This information acts as a guide for prioritizing marketing efforts and refining inventory tactics to meet specific local demands.

### Key Insights

- In-depth analysis of sales trends, product performance, geographical distribution, and order volumes offers actionable insights crucial for refining the company's business strategy.
- Focusing on popular product categories is instrumental in driving sustained growth and bolstering revenue streams.
- Proactive inventory management, particularly during peak sales periods, is imperative to prevent stockouts and optimize revenue potential.
- Targeted marketing efforts tailored to high-demand regions hold significant promise for augmenting sales performance.

### Conclusion

The Electronics Sales Insight Dashboard acts as a powerful resource for extracting valuable insights from sales data, enabling strategic decision-making within the company. Informed by these insights, key strategies involve strengthening inventory and marketing efforts during peak sales seasons, leveraging successful product categories, refining pricing strategies, and customizing marketing campaigns for regions with increased demand. By putting these insights into practice, the company can improve its competitive edge and tap into previously unexplored sales opportunities.

### Appendix

A sample excerpt from the raw dataset utilized for analysis is presented below:

```
| Order ID | Product                   | Quantity Ordered | Price Each | Order Date          | Purchase Address                      |
|----------|---------------------------|------------------|------------|---------------------|---------------------------------------|
| 176558   | USB-C Charging Cable     | 2                | 11.95       | 04/19/19 08:46      | 917 1st St, Dallas, TX 75001         |

| 176559   | Bose SoundSport Headphones | 1              | 99.99       | 2004-07-19 22:30    | 682 Chestnut St, Boston, MA 02215    |
| 176560   | Google Phone             | 1                | 600.00      | 2004-12-19 14:38    | 669 Spruce St, Los Angeles, CA 90001 |
| 176560   | Wired Headphones         | 1                | 11.99       | 2004-12-19 14:38    | 669 Spruce St, Los Angeles, CA 90001 |
| 176561   | Wired Headphones         | 1                | 11.99       | 04/30/19 09:27      | 333 8th St, Los Angeles, CA 90001    |
| 176562   | USB-C Charging Cable     | 1                | 11.95       | 04/29/19 13:03      | 381 Wilson St, San Francisco, CA 94016|
| 176563   | Bose SoundSport Headphones | 1              | 99.99       | 2004-02-19 07:46    | 668 Center St, Seattle, WA 98101     |
| 176564   | USB-C Charging Cable     | 1                | 11.95       | 2004-12-19 10:58    | 790 Ridge St, Atlanta, GA 30301       |
| 176565   | Macbook Pro Laptop       | 1                | 1700.00     | 04/24/19 10:38      | 915 Willow St, San Francisco, CA 94016|
| 176566   | Wired Headphones         | 1                | 11.99       | 2004-08-19 14:05    | 83 7th St, Boston, MA 02215          |
| 176567   | Google Phone             | 1                | 600.00      | 04/18/19 17:18      | 444 7th St, Los Angeles, CA 90001    |
| 176568   | Lightning Charging Cable | 1                | 14.95       | 04/15/19 12:18      | 438 Elm St, Seattle, WA 98101        |
| 176569   | 27in 4K Gaming Monitor   | 1                | 389.99      | 04/16/19 19:23      | 657 Hill St, Dallas, TX 75001        |

```

For a visual preview of the dashboard, please refer to the following link:
[Electronics Sales Insight Dashboard](https://www.novypro.com/project/electronics-sales-insight-dashboard-power-bi)
```

