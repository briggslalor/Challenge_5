# Challenge_5

This project creates a retirement planner and emergency fund calculator. The project grabs the current prices of different cryptocurrencies and stocks and bonds to use in calculating the current value of a given retirement fund and determine whether or not it is large enough to create a secondary emergency fund. In addition, it runs a series of Monte Carlo simulations on differently weighted retirement portfolios to determine if there is a chance for an earlier retirement. 

---

## Technologies

This project requires Python 3 and Jupyter Labs in order to run. In addition it requires the following libraries to be imported for proper function.

  [os](https://docs.python.org/3/library/os.html)
  
  [requests](https://docs.python.org/3/library/os.html)
  
  [json](https://docs.python.org/3/library/json.html)
 
  [pandas](https://pandas.pydata.org/)
  
  [dotenv](https://pypi.org/project/python-dotenv/)
  
  [alpaca_trade_api](https://alpaca.markets/docs/api-documentation/)
  
  ---
  
  ## Installation Guide 
  
  The required libraries and functions for this project can be imported using the following code:
  
  ```python 
  import os
  import requests
  import json
  import pandas as pd
  from dotenv import load_dotenv
  import alpaca_trade_api as tradeapi
  from MCForecastTools import MCSimulation

  %matplotlib inline
```

---

## Usage 

This project is built to be opened and run from an IDLE, like Jupyter Labs. When it is opened and run, it will generate all of the calculations and functions that it runs. Throughout the project, the results will be displayed. 

---

## Contributors

This project was buily by Briggs Lalor.
email: briggsclalor@gmail.com

---

## License

MIT License

Copyright (c) [2021] [Briggs Lalor]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
  
