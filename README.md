# stock-analysis
Week 2 VBA Challenge


##Project Overview
  The purpose of the project was the study the annualized returns of 12 stock tickers that were being held within Steve's Parents portfolio. Metrics were collected for the years 2017 and 2018 then a VBA script was constructed to efficently analysis the provided data.
  
  ##Results
    When analyzing the 2017 data, the code ran in 0.2734375 seconds, for the year 2018 the code ran in 0.171875 seconds. The final analysis matches the analysis performed in the Modules for this week, so I am confident that the VBA script refactored is correct, also the code runs faster than it did in the Modules which was designed to do so.
    
    ##Summary
    Advantages of the refactoring code (in general) revolve around the idea of code optimization and efficency. Disadvanges include additional errors when reorganizing and/or structuring code as well as copy/pasting code from external sources.
    
    Advantages of our refactored code (specific to this project) include the ability for the code to run in a faster time. This is because our refactored code collects the volume and price data for each ticker as the script loops through the tickers, whereas the original code collects the volume and price data for a single ticker within each loop then starts again with the next ticker.
