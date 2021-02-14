# A CLI calculator to calculate return on investments.

Usage:

stonks [-h] -p PRINCIPAL (-y YEARS | -t) (-r ROI | -s SYMBOL)

A CLI ROI calculator. Prints out the final value of an investment in a table format,
or for a specific year.

optional arguments:

  -h, --help            show this help message and exit
  
  -p PRINCIPAL, --principal PRINCIPAL
  
                        The initial investement as a dollar amount.
                        
  -y YEARS, --years YEARS
  
                        The number of years the investment will be held.
                        
  -t, --table           Rather than get the ROI for a single time value, outputs a
                        table with ROIs for multiple time values.
                        
  -r ROI, --roi ROI     A percentage value used to calcuate yearly interest. Ex:
                        11.5
                        
  -s SYMBOL, --symbol SYMBOL
  
                        The trading symbol. The program scrapes the ROI from a web
                        page. Ex: SWPPX

![Gif of Application at Work](./table_format.gif "A look at the application at work")

### Coming Soon:
Use a trading symbol to get the ROI from the internet.
