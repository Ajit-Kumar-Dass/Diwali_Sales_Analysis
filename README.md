# Diwali Sales Analysis 🪔📈

Hey there! This is my small project where I dove into Diwali sales data to figure out who’s actually shopping the most during the festival and what they’re buying.

I used Python in a Jupyter Notebook — nothing fancy, just Pandas, Matplotlib and Seaborn to clean the data and create some clear visualizations. It was fun seeing the patterns pop out!

## What I wanted to find out

Basically, I was curious about questions like:

- Are women or men buying more during Diwali?
- Which age group goes crazy with shopping?
- Which states light up the sales chart?
- What kind of jobs do the biggest spenders have?
- Which products fly off the shelves the most?

These kinds of answers can really help shops/stockists plan better for next Diwali — stock more of what sells, target the right people, etc.

## The Data

File: [Diwali Sales Data.csv](./Python_Diwali_Sales_Analysis/Diwali%20Sales%20Data.csv)

It’s a classic dataset you see in a lot of beginner-to-intermediate Python EDA projects — around 11–15 thousand rows with columns like:

- User_ID / Order_ID  
- Gender  
- Age / Age Group  
- Marital_Status  
- State  
- Occupation  
- Product_Category  
- Amount (sales value)  
- Orders  

Super useful for seeing real customer behavior.

## What I found (the fun part!)

Here are some of the clearest patterns that came out:

- **Women are leading the charge** — they bought way more than men during Diwali.  
- **26–35 age group dominates** — especially women in this bracket. They seem to have both the interest and the budget!  
- **Married folks spend more** — particularly married women.  
- **Top states by sales**: Uttar Pradesh, Maharashtra, Karnataka usually take the top spots (followed by Delhi, Madhya Pradesh, etc.).  
- **Occupations driving sales**: IT sector, Healthcare, Aviation — people in these fields were spending the most.  
- **Best-selling categories**: Food, Clothing & Apparel, Electronics & Gadgets — these three categories brought in the biggest revenue.

I’ve got bar charts, count plots and a few other visuals in the notebook showing all this step-by-step.

## Tech I used

- Python (of course!)  
- Jupyter Notebook  
- Pandas → for cleaning and crunching numbers  
- NumPy → whenever needed  
- Matplotlib + Seaborn → made the charts look decent  

That’s pretty much it — kept it simple.

## How to check it out yourself

1. Clone the repo:
   ```bash
   git clone https://github.com/Ajit-Kumar-Dass/Diwali_Sales_Analysis.git
