# LAB: Python for Data Analysis - Data Visualization Techniques

![Excel Image](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

## Introduction

Hello everyone! In this session, we will explore the use of pandas, Matplotlib, and Seaborn to enhance your data visualization skills. This includes learning how to create visually appealing charts and graphs, narrate the story behind your data, and uncover actionable insights from it. Imagine you are part of a small team at a company, and you need to visually represent and analyze the team's data using Python. This lab will empower you with the techniques to craft compelling visual representations of datasets, making you more effective in your data handling roles.

## Initial Setup

## Requirements
Start by forking the provided GitHub repository to your account and then clone it locally. This will be your workspace for completing the lab exercises.
- [Learn how to fork this repo](https://guides.github.com/activities/forking/)
- Clone this repo into your `code/labs` folder

## Scenario

Imagine you are a junior data analyst at a retail company. Your manager has asked you to analyze the sales trends for various products over the year to inform upcoming marketing strategies. Your task is to visualize this data, identifying seasonal trends, product popularity, and potential opportunities for sales campaigns.
## Starter Code

You have to solve the different problems in the `LAB-Data-Visualization.ipynb` notebook.

To get started, follow these steps:

1. Open your terminal and navigate to the `cloned-repo` directory:

    ```bash
    cd path/to/your/cloned-repo/
    ```

2. Launch Jupyter Notebook:

    ```bash
    jupyter lab
    ```

3. In the Jupyter Notebook interface, open the `LAB-Data-Visualization.ipynb` file.

To test that everything is set up correctly, run the first cell in the notebook. This cell usually contains import statements and initial setup code. If it runs without errors, you are ready to start solving the exercises.

You can write and execute your code in the provided cells within the notebook. Any outputs, including print statements and visualizations, will be displayed directly in the notebook, making it easy to debug and verify your solutions.

## Iteration 0: Install Dependencies

Make sure you have all the necessary libraries installed by using the `requirements.txt` file provided. You can install the dependencies with the following command:

```bash
pip install -r requirements.txt
```

## Iteration 1: Plotting with Matplotlib

In this iteration, you will learn to use Matplotlib, a data visualization library in Python, to create basic but informative charts. We will start by loading and understanding the dataset structure, followed by creating various types of charts to visualize monthly sales, sales trends over time, and the relationship between sales and discounts.

#### Dataset Description

The dataset includes the following columns:

- Date: The date of the sale.
- Product Category: The category of the product (Electronics, Clothing, etc.).
- Sales: The total monetary value generated from the sale.
- Discount: The percentage discount applied.
- Region: The region where the sale occurred (North, South, East, West).
- Promotion: Indicates whether the sale was part of a promotion ("Yes" or "No").

### 1.1 Bar Plot: Monthly Sales

- Load the dataset and create a **bar plot** to visualize the **total sales per month**.
- Add annotations to show the exact sales value on top of each bar.

This plot will help identify sales patterns over the year.

### 1.2 Line Plot: Seasonal Sales Trends

- Using the monthly sales from the previous bar plot, create a **line plot** to visualize **seasonal sales trends**.

This will help to identify peaks and dips in sales over the year.

### 1.3 Scatter Plot: Relationship Between Discounts and Sales

- Create a **scatter plot** to explore the relationship between the **discount percentage** and the **sales value**.

---

## Iteration 2: Advanced Analysis with Seaborn

### 2.1 Heatmap: Correlations Between Variables

- Use a **heatmap** to visualize correlations between the numerical variables in the dataset (e.g., **Sales** and **Discount**).

> **Note:** When working with datasets that contain both numerical and categorical data, it's important to select only the numerical columns before calculating the correlation matrix. In Python's `pandas`, we can use the method `select_dtypes(include=[float, int])` to filter out only the columns with numeric data types, such as integers and floats.

This will help detect important relationships between the variables.

### 2.2 Histogram: Sales Distribution by Product Category

- Create a **histogram** to compare the **sales distribution** across different **product categories**.

This will reveal which categories generate the most revenue and how sales are distributed within each category.

### 2.3 Bar Plot: Sales by Region

- Create a **bar plot** to show **total sales by region**.

This will help identify which regions are driving the most sales and compare performance between regions.

---

## Iteration 3: Customizing Visualizations for Presentation

### 3.1 Enhance Visualizations

- **Monthly Sales Bar Plot**: Customize the monthly sales bar plot from **Iteration 1.1** by adding annotations and adjusting the visual style for a more presentable appearance.

### 3.2 Apply Seaborn Styles

- Experiment with different Seaborn styles (such as `'darkgrid'`, `'whitegrid'`, etc.) to improve the appearance of the plots created in **Iterations 1 and 2**.

---

## Iteration 4: Business Insights and Conclusions

### 4.1 Seasonal Sales Trends

- Use the **line plot** from **Iteration 1.2** to identify sales peaks in specific months and analyze any **seasonal patterns**.

### 4.2 Product Category Performance

- Use the **histogram of sales by category** from **Iteration 2.2** to identify which product categories perform best throughout the year.

### 4.3 Impact of Promotions

- Create a **scatter plot** to show the **impact of promotions** on sales, distinguishing between sales with and without promotions.

This plot will help explore whether promotions have a significant effect on boosting sales.

### 4.4 Sales Distribution Over Time

- Use the **monthly sales bar plot** from **Iteration 1.1** to analyze the **distribution of sales** over time.

### 4.5 Sales Variability by Product Category

- Use a **box plot** to visualize the **variability of sales by product category**. This will help understand which categories have more stable or fluctuating sales.

> **Hint**: [Box Plot Documentation](https://seaborn.pydata.org/generated/seaborn.boxplot.html)

## Bonus Challenge

### Interactive Visualizations

1. Integrate interactive elements into your visualizations using Plotly.
   - Convert one of the existing plots into an interactive visualization using Plotly.

### Dashboard Layout

2. Explore and implement subplots to create a dashboard-like layout of multiple plots.
   - Create a dashboard layout with multiple subplots to show different aspects of the sales data in a single visualization.

### Advanced Seaborn Visualizations

- **Violin Plot:** Investigate and create a violin plot to visualize the distribution and density of sales by product category. Refer to the Seaborn documentation for guidance.
- **Box Plot:** Explore and create a box plot to compare sales distributions between different product categories. Use the Seaborn documentation as a resource.
- **Cat Plot:** Research and create a cat plot to analyze sales in different regions. Consult the Seaborn documentation for help.

## Submission
Once you have completed your analysis and visualizations, push your Jupyter notebook to your forked GitHub repository. Ensure that your final submission includes narratives explaining your visualizations and insights.
Run the following commands:

```
$ git add .
$ git commit -m "done"
$ git push origin main
```

Then create a Pull Request!!

## Additional Resources

- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html).
- [Seaborn Documentation](https://seaborn.pydata.org/).
- [Python Graph Gallery](https://www.python-graph-gallery.com/) for inspiration and code snippets.
- [Plotly Documentation](https://plotly.com/python/).


![happy_coding](https://user-images.githubusercontent.com/970858/63899010-c23fc480-c9ea-11e9-84a2-542907e42362.png)
