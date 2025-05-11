# Prompt Engineering in Action: Building a Functional Web-Based HTML Dashboard with ChatGPT

## Project Overview

This project is an interactive Sales Performance Dashboard built using HTML. It allows users to upload their sales data in JSON format from their local computer and dynamically generates a visual dashboard. The dashboard was designed through prompt-based development using ChatGPT, where each step focused on identifying effective visual metrics, implementing interactivity, and enhancing visual aesthetics.

## Key Visual Metrics and Design Rationale

The first step in the development process was to analyze the structure of the uploaded JSON sales data. Based on the fields such as Date, Product, Revenue, and Units Sold, five key visualizations were identified as most impactful:

	1.	Revenue Over Time (Line Chart) – Helps in tracking sales trends and identifying peak performance periods.
	2.	Units Sold by Product (Bar Chart) – Useful for comparing which products perform best in terms of quantity sold.
	3.	Total Revenue by Product Category (Pie Chart) – Provides a quick overview of revenue distribution across categories.
	4.	Top 5 Performing Products (Horizontal Bar Chart) – Highlights products driving the highest revenue.
	5.	Monthly Sales Growth (Area Chart) – Allows visualizing cumulative or comparative month-over-month growth.

Each of these visualizations was selected for its ability to communicate insights at a glance and support performance tracking and decision-making.

## How to Use the Dashboard
	1.	Open Sales_Dashboard.html in any modern web browser.
	2.	Click the “Upload JSON” button and select your sales data file.
	3.	The dashboard will automatically generate five visualizations based on your data.
	4.	Use the visuals and KPIs to explore your sales performance.

## Prompt_ChatGPT

### Prompt 1
This is the structure of my sales data in JSON format. Understand the structure and suggest five key data visualization metrics that would be the best fit to create an interactive sales dashboard. Also explain why we should use each one?

### Prompt 2
Now, I want you to create an interactive sales performance dashboard with the five key visualizations using HTML and JavaScript. Use the latest version of Plotly.js CDN and include an upload feature so that we can upload the JSON file. It should generate the dashboard based on the uploaded data.

### Prompt 3
Provide this as an HTML downloadable file?

### Prompt 4
From the dashboard you created, change the style to glass morphism. Then, adjust the padding width of the charts to 40%, and change the background colour to icy blue. Can you also provide this as a downloadable HTML file?

## Key Challenges

One of the key challenges in this project was ensuring the layout, visual styling, and functionality came together without writing complex manual code. Since the entire dashboard was built through ChatGPT, it required very clear and intentional prompt design. I had to carefully craft each instruction and often revise the wording to guide the model correctly. This highlighted a crucial insight: defining a prompt clearly—whether as a single-shot or few-shot—is essential to generating high-quality, structured responses. It also emphasized the importance of understanding token (word) limits in large language models, as exceeding those limits can lead to incomplete or broken outputs.


### *** I have also created a updated version of HTML file just extra visual background ***
