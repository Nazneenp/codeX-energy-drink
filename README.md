# **Data Analysis Project: codeX Energy Drink**  
> Data analysis project using Python libraries like Pandas, Matplotlib, and NumPy to uncover insights from survey of codeX engegy drink.

## **Table of Contents**
- [Introduction](#introduction)
- [Objective](#objective)
- [Technologies Used](#technologies-used)
- [Dataset Details](#dataset-details)
- [Key Analysis Performed](#key-analysis-performed)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Results and Insights](#results-and-insights)
- [Acknowledgments](#acknowledgments)

## **Introduction**
1. This project involves analyzing a survey respomse dataset to derive meaningful insights and trends.  
2. The analysis uses Python libraries such as Pandas for data manipulation, NumPy for numerical computations, and Matplotlib/seaborn for data visualization.  
3. The goal is to help stakeholders understand sales patterns, customer behavior, and product performance.

## **Objective**
The objectives of this project include finding insight of the following:
1. Demographic Insights 
2. Consumer Preferences 
3. Competition Analysis 
4. Marketing Channels and Brand Awareness 
5. Brand Penetration
6. Purchase Behavior 
7. Product Development

## **Technologies Used**
The project leverages the following tools and libraries:
- **Python:** Programming language for data analysis.
- **Pandas:** For data cleaning, manipulation, and exploration.
- **NumPy:** For numerical calculations.
- **Matplotlib:** For data visualization.
- **seaborn:** For data visualization.

## **Dataset Details**
- **Description:** [Link to meta_data.txt file](https://github.com/Nazneenp/codeX-energy-drink/blob/main/meta_data.txt)
- **Data Preprocessing:**
  - Handled missing values in the `dim_repondents` table.

## **Key Analysis Performed**
1. **Data Cleaning and Preprocessing:**
   - Removed duplicate entries.
   - Imputed missing data for consistency.
2. **Descriptive Statistics:**
   - Calculated mean, median, and standard deviation for sales data.
3. **Trend Analysis:**
   - Analyzed monthly sales trends using line plots.
4. **Top Performers City:**
   - Identified top 10 citys by revenue.
5. **Customer Behavior:**
   - Explored purchase patterns based on categories and regions.
6. **Visualizations:**
   - Created bar charts, line graphs, and pie charts to visualize findings.

## **Installation**
To run this project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Nazneenp/codeX-energy-drink.git
   cd codeX-energy-drink
   ```
2. Install the required dependencies:
    ``` bash
    pip install -r requirements.txt
    ```
3. Run the primary_insights.ipynb filr to see the analysis

## **Project Structure**
``` plaintext
📦 codeX-energy-drink
 ┣ 📂 data
 ┃ ┣ 📜 dim_cities.csv
 ┃ ┣ 📜 dim_repondents_updated.csv
 ┃ ┣ 📜 dim_repondents.csv
 ┃ ┗ 📜 fact_survey_responses.csv
 ┣ 📂 notebooks
 ┃ ┣ 📜 data_cleaning.ipynb
 ┃ ┣ 📜 primary_insights.ipynb
 ┃ ┗ 📜 secondary_insights.ipynb
 ┣ 📜 LICENSE.txt
 ┣ 📜 meta_data.txt
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
 ┗ 📜 Survey_Questions_and_Response_Options.pdf
```

## **Results and Insights**
Key Findings:

1. Immediate improvements:
    - Improve distribution in Tier 1 cities, with a priority on Bangalore, which has the highest demand.  
    - Address the availability gap in top cities to meet consumer needs effectively.  
    - Enhance the product's taste as the overall rating is currently average.  
2. Ideal price:
    - Analyze pricing by age group, limited edition packaging, and city tier for better targeting.  
    - Set a price range of ₹50-99 in Tier 1 and Tier 2 cities for regular packaging.  
    - Offer limited edition packaging at a premium price of ₹100-150 to attract niche customers.  
3. Marketing campaigns, offers, and discounts:
    - Leverage online ads for marketing, as they perform well across all demographics and city tiers.  
    - Offer limited edition packaging at a discounted price of ₹50-99 to boost appeal.  
4. Brand Ambassador, and why:
    - Choose Arshdeep Singh as the brand ambassador, aligning with the energy drink's association with sports and exercise, as he is a cricketer.  
    - Highlight Arshdeep’s role as a left-arm medium-fast bowler, requiring energy and focus, which resonates with the product's benefits.  
    - Leverage his popularity after bowling the winning over in the T20 World Cup, making him a relatable and impactful figure.  
    - Capitalize on his recent rise in fame following India’s T20 World Cup win after 18 years.  
5. Target audience, and why:
    - Target young adults aged 15-30, as they form the majority of our buyer demographic.  
    - Focus on Tier 1 cities, where most of our customers are located.  

## **Acknowledgments**
This project used:
- Python libraries: Pandas, NumPy, Matplotlib.
- Tutorials and documentation from Python.org and Matplotlib.
