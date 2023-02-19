# Financial_Planner_Tool

This program aims to provide key information to the members of the credit union. The information include if the members have enough money in their emergency fund. The program also use Monte Carlo simulations to provide risk and return insights as to whether it makes sense for the members to retire after 10 years or 30 years.

---

## Technologies

The technologies required to use for this project on either Mac or PC include:

Python 3.11.1

Jupyter Lab

Requests

Json

Panda

Dotenv

Alpaca API including required keys

Monte Carlo Simulations


---

## Installation Guide

In order to run the program, insert and run the following commands in a Jupyter notebook :

`import os`

`import requests`

`import json`

`import pandas as pd`

`from dotenv import load_dotenv`

`import alpaca_trade_api as tradeapi`

`from MCForecastTools import MCSimulation`

`%matplotlib inline`


Please make sure to register with Alpaca API and copy your API key and secret key into your env file.
`Once load_dotenv()` returns `True` you can continue to the next steps.

---

## Contributors

Soheil Gityforoze

sg3956@columbia.edu

[LinkedIn](https://www.linkedin.com/feed/)

---

## License

MIT License

Copyright (c) [2023]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
