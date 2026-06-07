# 6-univariate-bivariate-multivariate-(NPMS)
# Supermarket Sales - Univariate, Bivariate, and Multivariate Analysis

This project is an exploratory data analysis (EDA) focused on examining supermarket transaction records. The analysis implements univariate, bivariate, and multivariate statistics alongside visualizations with Seaborn and Matplotlib to study customer demographics, branch performance, product line success, and core financial relationships.


## Project Structure

The repository includes:
* **`6_univariate_bivariate_multivariate_answers.ipynb`**: The Jupyter Notebook containing the data exploration steps, descriptive statistical formulas, and visualization plots.
* **`6univariatebivariatemultivariate.csv`**: The dataset tracking transactional information, customer choices, and sales results from different supermarket branches.


## Tech Stack & Dependencies

* **Language:** Python 3.x
* **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / JupyterLab


## Dataset Overview

The `6univariatebivariatemultivariate.csv` dataset contains information across the following 17 attributes:
* **Invoice ID:** Unique identification number assigned to each computer-generated invoice sales slip.
* **Branch:** Supermarket branch designation identifier (A, B, or C).
* **City:** Location city of the operating store.
* **Customer type:** Type of customer, categorized as Member for cardholders or Normal for standard users.
* **Gender:** Gender profile of the customer.
* **Product line:** Broad item category classification (e.g., Electronic accessories, Health and beauty, Food and beverages).
* **Unit price:** Product price per single item itemized in US Dollars ($).
* **Quantity:** Total count of individual items purchased per invoice slot.
* **Tax 5%:** Total internal tax fee added onto the purchase price check.
* **Total:** Cumulative transactional check value including final tax calculations ($).
* **Date:** The calendar date when the checkout occurred.
* **Time:** The checkout clock time tracking store window traffic hours.
* **Payment:** Selected payment settlement system utilized (Cash, Credit card, or Ewallet).
* **cogs:** Cost of goods sold tracking inventory baseline asset valuations ($).
* **gross margin percentage:** Computed gross margin percentage index baseline.
* **gross income:** Realized gross income generated over the checkout transaction ($).
* **Rating:** Customer satisfaction survey feedback score recorded on a scale from 1 to 10.


## Key Tasks & Insights Covered

The notebook approaches data analysis by breaking operations down into three distinct statistical categories:

1. **Univariate Analysis:** Inspecting isolated single attributes. This includes looking at general data shapes, finding value counts across categorical elements (like checking month-by-month traffic volumes), and plotting basic bar plots or distribution graphs to assess single columns in a vacuum.
2. **Bivariate Analysis:** Evaluating interactions between two variables simultaneously. This covers charting categorical groupings against numeric sales indicators, looking into features like total revenue patterns or user satisfaction metrics across different payment platforms, and examining how specific gender attributes spread across distinct product lines.
3. **Multivariate Analysis:** Analyzing multiple variables concurrently to find complex patterns. The analysis utilizes Seaborn heatmap functions to build correlation matrix grids, map linear relationships, and trace how several operational metrics interact simultaneously.


## How to Run This Project

Choose the option below that works best for you:

### Option 1: The Quick Way (No Git Required)
1. Click the green **Code** button at the top right of this GitHub page.
2. Click **Download ZIP** and unzip the files into a folder on your computer.
3. Move your dataset (`6univariatebivariatemultivariate.csv`) into the same folder if it isn't already there.
4. Open your terminal or command prompt, navigate to that folder, and run:
   ```bash
   pip install pandas numpy matplotlib seaborn notebook
   jupyter notebook


## Author

Priya Patel  
Aspiring Data Analyst  
Email: patelpriya18217@gmail.com   
GitHub: [priyapatel96140](https://github.com/priyapatel96140)  

If you like this project, feel free to give it a star!
