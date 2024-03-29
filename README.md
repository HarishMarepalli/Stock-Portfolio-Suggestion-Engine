This project provides a stock portfolio suggestion engine for the user.

User will:

  Input dollar amount to invest in USD (Minimum is $5000 USD)
  
  Pick one or two investment strategies:
  
    Ethical Investing
    
    Growth Investing
    
    Index Investing
    
    Quality Investing
    
    Value Investing
    
The engine needs to assign stocks or ETFs for a selected investment strategy. E.g.

Index Investing strategy could map to the following ETFs:

  Vanguard Total Stock Market ETF (VTI)
  
  iShares Core MSCI Total Intl Stk (IXUS)
  
  iShares Core 10+ Year USD Bond (ILTB)
  
And

Ethical Investing strategy could map to these stocks:

  Apple (APPL)
  
  Adobe (ADBE)
  
  Nestle (NSRGY)
  
Each strategy must map to at least 3 different stocks/ETFs.

 

Output:

The suggestion engine will output:

  Which stocks are selected based on inputed strategies.
  
  How the money are divided to buy the suggested stock.
  
  The current values (up to the sec via Internet) of the overall portfolio (including all the stocks / ETFs)
  
  A weekly trend of the portfolio value. In order words, keep 5 days history of the overall portfolio value.
