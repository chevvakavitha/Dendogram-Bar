# Dendrogram & Bar Chart Visualization with D3.js

**Created by:** Cheva Kavitha

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Dataset](#dataset)
4. [Dendrogram Visualization](#dendrogram-visualization)
5. [Bar Chart Visualization](#bar-chart-visualization)
6. [Features](#features)
7. [Usage](#usage)
8. [Conclusion](#conclusion)

---

## Project Overview
This project demonstrates how to use **D3.js** to create two powerful visualizations:
- **Dendrogram (Tree Diagram)**: A hierarchical tree structure used to represent the relationships within data.
- **Bar Chart**: A traditional data visualization used to represent categorical data with bars.

Both visualizations are interactive and allow users to explore complex data relationships and trends. 
The dendrogram provides a clear picture of hierarchical structures, while the bar chart gives a simple yet effective view of category-based data.

The project is designed to work in a web browser, allowing for smooth, interactive exploration of data visualizations.

---

## Technologies Used
- **D3.js**: A JavaScript library used to manipulate documents based on data and create interactive visualizations.
- **HTML**: The structure of the web page.
- **CSS**: For styling the visualizations and page layout.
- **JavaScript**: For interactivity and integrating D3.js into the web page to visualize the data.

---

## Dataset
The dataset used in this project consists of both hierarchical and categorical data. It contains:
- **Dendrogram Data**: Data organized in a tree-like structure with multiple levels and relationships between nodes.
- **Bar Chart Data**: Categorical data, where each category has a corresponding value (e.g., sales per product, rating per category, etc.).

This dataset allows the user to visualize complex relationships through the dendrogram and compare categories with the bar chart.

---

## Dendrogram Visualization
![Screenshot (384)](https://github.com/user-attachments/assets/4682c694-830f-4fc6-bb22-3b5e13d2858a)
The Dendrogram is used to represent hierarchical data in a tree-like structure. Each node represents a data point, and the branches indicate relationships between them. 
This visualization is especially useful for understanding groupings, categories, and levels within data.

### Features of the Dendrogram:
- Interactive zooming and panning to explore deep levels of hierarchy.
- Tooltips that provide more information when hovering over nodes.
- Collapse and expand options for nodes to simplify the tree structure for better clarity.

---

## Bar Chart Visualization
The Bar Chart is used to represent categorical data with bars of varying lengths. Each bar represents a category, and its length corresponds to the value for that category.
This is ideal for comparing values across different categories.

### Features of the Bar Chart:
- Interactive sorting and filtering to analyze data in various ways.
- Color-coded bars for better visualization of trends.
- Hover effects that display exact values when the user interacts with each bar.

---

## Features
- **Interactive Visualizations**: Both the dendrogram and bar chart are fully interactive, allowing users to explore the data by zooming, panning, and hovering for more details.
- **Responsive Design**: The visualizations adapt to different screen sizes and devices for a seamless experience on both desktop and mobile platforms.
- **Real-time Data Update**: The visualizations update dynamically based on any changes made to the dataset or filters applied.

---

## Usage
To use this project locally:
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/d3-dendrogram-bar-chart.git

---

## Conclusion
This project showcases how powerful D3.js can be when creating interactive data visualizations. By using a Dendrogram and a Bar Chart, 
the project offers two different ways of visualizing data: hierarchical relationships and categorical comparisons. 
These tools help users to uncover insights from complex data structures and make informed decisions.

Whether you're analyzing data relationships or comparing category-wise performance, this project provides a clear and interactive way to explore your data.
By combining D3.js's flexibility and powerful visualization capabilities, this project serves as an example of how data visualization can simplify the understanding of complex datasets.
