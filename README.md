# LAB: Python for Data Analysis - Data Visualization Techniques

![Excel Image](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

## Introduction

Welcome to the Data Visualization Techniques lab. In this session, you will practice your knowledge of pandas, Matplotlib, and Seaborn. Data visualization is not just about making attractive graphics—it's about telling stories and making insights and data visible and actionable. This lab will equip you with the skills to create compelling visual representations of datasets.

## Initial Setup

### Fork and Clone the Repository
Start by forking the provided GitHub repository to your account and then clone it locally. This will be your workspace for completing the lab exercises.

## Scenario

You are working as a junior data analyst at a retail company. Your manager wants to understand the sales trends for different products throughout the year to aid in upcoming marketing strategies. You've been tasked with visualizing this data to identify seasonal trends, product popularity, and potential areas for sales campaigns.

## Iteration 1: Plotting with Matplotlib

In this iteration, you will learn to use Matplotlib, a data visualization library in Python, to create basic but informative charts. We will start by loading and understanding the dataset structure, followed by creating various types of charts to visualize monthly sales, sales trends over time, and the relationship between sales and discounts.

1. Load the dataset (focus on sales data).
   - **Instruction:** Use pandas to load the provided CSV file and inspect the first few rows to understand its structure.

#### Visualize Monthly Sales

2. Use Matplotlib to plot a bar chart showing sales per month.
   - **Instruction:** Create a bar chart where the X-axis represents the months of the year and the Y-axis represents the total sales for each month.

3. Customize your plot with labels and a title to improve readability.
   - **Instruction:** Add a title, axis labels, and customize the colors of the bars.

#### Analyze Sales Trends

4. Create a line plot to show the sales trend over time.
   - **Instruction:** Create a line plot with total sales per month to identify trends over the year.

#### Explore Sales and Discounts Relationship

5. Create a scatter plot to analyze the relationship between sales and discounts.
   - **Instruction:** Create a scatter plot where the X-axis represents discounts and the Y-axis represents sales.

## Iteration 2: Plotting with Seaborn

In this iteration, you will leverage Seaborn, a statistical data visualization library in Python, to create more advanced plots. We will create a correlation heatmap, pair plots to explore relationships between variables, histograms to compare sales distributions, and bar plots for regional sales analysis.

#### Correlation Heatmap

1. Generate a heatmap to visualize sales data correlations.
   - **Instruction:** Create a heatmap showing correlations between different numerical variables in the dataset.

#### Product Category Analysis

2. Create a pair plot to explore relationships between continuous variables in different product categories.
   - **Instruction:** Generate a pair plot including variables such as sales, discounts, and other relevant factors to analyze possible relationships within product categories.

#### Sales Distribution by Category

3. Create histograms to compare sales distributions between different product categories.
   - **Instruction:** Create histograms comparing sales across different product categories.

#### Regional Sales Analysis

4. Create a bar plot to analyze sales in different regions.
   - **Instruction:** Create a bar plot showing sales across different geographical regions.

## Iteration 3: Customizing Plots for Insights

In this iteration, you will learn how to enhance your visualizations by adding annotations, using color maps, and adjusting axes properties to improve clarity and visual appeal. You will also experiment with Seaborn’s styles and color palettes to prepare presentation-ready figures.

#### Enhance Visualizations

1. Enhance your plots from previous iterations by adding annotations, using color maps, and adjusting axes properties for clarity and visual appeal.
   - **Instruction:** Add annotations to bar charts and heatmaps to highlight important points. Adjust axis limits and experiment with different color maps.

#### Presentation-Ready Figures

2. Experiment with Seaborn’s styles and color palettes to prepare presentation-ready figures.
   - **Instruction:** Apply different Seaborn styles and color palettes to the created plots to improve visual presentation.

## Iteration 4: Comprehensive Business Insights

In this final iteration, you will synthesize your visualizations to gain comprehensive business insights. You will analyze seasonal sales trends, compare product category performance, evaluate the impact of promotions, and visualize sales distribution and variability over time. Finally, you will summarize your findings and prepare a presentation for stakeholders.

#### Seasonal Sales Trends

1. Create a line chart to show seasonal sales trends.
   - **Instruction:** Analyze how sales fluctuate over the months and identify any seasonal patterns.

#### Product Category Performance

2. Create a bar chart to compare the performance of different product categories over time.
   - **Instruction:** Evaluate which product categories perform best during different times of the year.

#### Impact of Promotions

3. Create a scatter plot to analyze the impact of promotions on sales.
   - **Instruction:** Determine how promotional activities affect sales numbers.

#### Sales Distribution Over Time

4. Create a histogram to show the distribution of sales over time.
   - **Instruction:** Visualize how sales are distributed across months to see overall sales performance.

#### Variability in Sales

5. Create a pair plot to visualize the relationships and variability of sales within each product category.
   - **Instruction:** Show the relationships and dispersion of sales by product category to understand sales variability.

#### Summarize Findings

6. Summarize your findings with visual aids and present them as if to a stakeholder.
   - **Instruction:** Prepare a presentation with the created visualizations, including a narrative explaining the most important findings.

## Bonus Challenge

### Interactive Visualizations

1. Integrate interactive elements into your visualizations using Plotly.
   - **Instruction:** Convert one of the existing plots into an interactive visualization using Plotly.

### Dashboard Layout

2. Explore and implement subplots to create a dashboard-like layout of multiple plots.
   - **Instruction:** Create a dashboard layout with multiple subplots to show different aspects of the sales data in a single visualization.

### Advanced Seaborn Visualizations

- **Violin Plot:** Investigate and create a violin plot to visualize the distribution and density of sales by product category. Refer to the Seaborn documentation for guidance.
- **Box Plot:** Explore and create a box plot to compare sales distributions between different product categories. Use the Seaborn documentation as a resource.
- **Cat Plot:** Research and create a cat plot to analyze sales in different regions. Consult the Seaborn documentation for help.

## How to Submit

Once you have completed your analysis and visualizations, push your Jupyter notebook to your forked GitHub repository. Ensure that your final submission includes narratives explaining your visualizations and insights.

## Dataset

The dataset provided for this lab is available at the following link: [Retail Sales Dataset](sandbox:/mnt/data/retail_sales_dataset.csv) (please make sure to load the file into your working environment).

## Additional Resources

- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html).
- [Seaborn Documentation](https://seaborn.pydata.org/).
- [Python Graph Gallery](https://www.python-graph-gallery.com/) for inspiration and code snippets.
- [Plotly Documentation]([https://matplotlib.org/stable/contents.html](https://plotly.com/python/)).


![happy_coding](https://user-images.githubusercontent.com/970858/63899010-c23fc480-c9ea-11e9-84a2-542907e42362.png)
