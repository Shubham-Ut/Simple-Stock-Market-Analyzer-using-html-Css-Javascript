# Simple-Stock-Market-Analyzer-using-html-Css-Javascript
💡 Overview:
This is an interactive stock portfolio optimization tool where you:

Enter the number of stocks.

Provide each stock’s name, price, and expected return.

Input your total investment budget.

The system calculates how many units of each stock to buy to maximize your expected return while staying within your budget.



->How It Works:
  1. User Input Section
  Number of Stocks: You input how many different stocks you want to analyze.

  After clicking "Generate Stock Inputs," input fields for each stock appear.

  For each stock, you input:

  Stock Name

  Price ($)

  Expected Return (%)

  2. Budget Input
  Enter your total budget.

  Click on "Optimize Portfolio."

  

  🧠 Optimization Logic (Greedy Algorithm):
In the improvedOptimization() function:

Stocks are sorted by highest expected return.

It allocates as much as possible to the stock with the highest return, then moves to the next.

This continues until the budget is exhausted or no more stocks can be bought.

This is a greedy approach, not an exhaustive one like dynamic programming — so it's fast, but may not be optimal in all cases. Still, it works well when you're looking for quick investment insights.


.

📊 Visualization:
The optimized results are displayed with:

Quantity of stocks

Investment per stock

Expected return

A bar chart is also generated to visually show how your budget is allocated across stocks.


🖼️ Design Highlights:
Modern UI: With gradient background, hover effects, and smooth animations.

Responsive and user-friendly.

Clean separation of logic and presentation.




