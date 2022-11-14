## PROJECT TITLE - ETF Analyzer

## PROJECT DESCRIPTION 
The objective of this project was to perform analysis on a Fintech ETF consisting of four stocks: GDOT, GS, PYPL and SQ. All the stocks daily returns were analyzed individually and as a whole.  Finally, the visualizations were deployed to a web application using the Voila library.

## PROJECT BREAKDOWN AND SUMMARY

<ul>
  <li>Analyze a Single Asset in the ETF - Use SQL queries with Python, Pandas and hvPlot to analyze the performance of a single asset from ETF.</li> 
  <li>Optimize Data Access with Advanced SQL Queries - Access closing prices of PYPL great than $200 and sorting out the top ten daily returns.</li> 
  <li>Analyze the ETF Portfolio - Build the ETF portfolio by using SQL joins to combine all the data from each asset.</li>
</ul>
Note: Please reference the file, etf_analyzer.ipynb, for the detailed instructional steps, Python Pandas code/dataframes, SQL queries and visualizations.<br>

## DEPLOY JUPYTER NOTEBOOK AS A WEB APPLICATION VIA THE VOILA LIBRARY

 1. Used terminal (Mac/Linux) or Command or Gitbash (Windows) to browse to the web application, web_app.ipynb.  
 2. Activated conda in development mode using the command, conda activate dev.
 3. Deployed the web application using the command, voila web_app.ipynb, and launched in an internet browser.
![Screenshot 2022-11-13 at 9 35 34 PM](https://user-images.githubusercontent.com/111409358/201619723-5fef79b0-e182-48ff-842a-a2c55d7d9fd6.png)
 4. The web application file, web_app.ipynb, is shown in the Jupyter notebook. 
<img width="1325" alt="Screenshot 2022-11-14 at 1 31 45 AM" src="https://user-images.githubusercontent.com/111409358/201625036-bc0624cb-ee5c-48f4-9ff7-294a8ca8f115.png">
 5. Confirmation of all the four table names, the top and bottom rows of PYPL Pandas dataframe and a visualization of PYPL daily returns between 2016 - 2020.<br>
 
![Screenshot 2022-11-13 at 9 23 33 PM](https://user-images.githubusercontent.com/111409358/201625631-d18c8cb2-92f6-4d16-869e-a1c336d82fd9.png)
 6. PYPL Cumulative Returns 2016- 2019 and an SQL query result read into a Pandas dataframe for closing prices for PYPL greater than $200.
![Screenshot 2022-11-13 at 9 24 10 PM](https://user-images.githubusercontent.com/111409358/201626100-a12d2ee6-5013-4345-b60b-5dad502033e3.png)
 7. Continuation of an SQL query result read into a Pandas dataframe for closing prices for PYPL greater than $200 and an SQL query for top 10 PYPL daily returns read into a Pandas dataframe and an SQL query for inner joined tables of GDOT, GS, PYPL and SQ, read into a Pandas dataframe.
 ![Screenshot 2022-11-13 at 9 24 33 PM](https://user-images.githubusercontent.com/111409358/201626117-aa0f575c-8dff-445f-b7f4-c91a5baa94f4.png)
 8. Continuation of SQL query for inner joined tables of GDOT, GS, PYPL and SQ, read into a Pandas dataframe and ETF portfolio returns. ETF portfolio returns, annualized ETF portfolio returns and ETF cumulative returns. 
![Screenshot 2022-11-13 at 9 24 55 PM](https://user-images.githubusercontent.com/111409358/201626140-cccf3374-ae3e-4534-b1d3-2397598482e2.png)
 9. Visualization of ETF portfolio cumulative returns.
![Screenshot 2022-11-13 at 9 25 22 PM](https://user-images.githubusercontent.com/111409358/201626164-cccd0cb2-edad-4c2f-aee4-c7a512c75fe2.png)

## CREDITS
Credit to all the teams: Data Analysts, Data Scientists, Product Development, Software Development and Web Development, for their contribution and participation in the project.

## LICENSE
None


