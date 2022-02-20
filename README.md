### Challenge 11


---


# Mercado Libre Predictions

## What this program does

In this program we have created the ability to 

---

## Technologies

This program can be run with Mac or Windows systems along with the following requirements:

Python 3.7.1

Jupyter Lab Notebooks

Google Colab

Facebook Prophet

Python Requests Library

Pandas Library including hvplot



---


## Installation Guide

First, to run in Google Colab, input the following code:

`from IPython.display import clear_output
try:
  !pip install pystan
  !pip install prophet
  !pip install hvplot
  !pip install holoviews
except:
  print("Error installing libraries")
finally:
  clear_output()
  print('Libraries successfully installed')`
  
Then make sure to run the appropriate imports:

`import pandas as pd`

`import hvplot.pandas`

`from pathlib import Path`

`import holoviews as hv`

`import numpy as np`

`from holoviews import opts`

`from prophet import Prophet`

`import datetime as dt`

`%matplotlib inline`


For more information about Google Colab, click [here](https://colab.research.google.com/?utm_source=scs-index)

For more information about FbProphet, click [here](https://facebook.github.io/prophet/)


---


## Usage


The following images can be seen when viewing this project:

![Bar Graph of Housing Unit Prices per Year in San Francisco](https://github.com/EmilyBertani/Challenge_6/blob/main/Bar_graph.png)

![Line Graph of Sale Price per Square Foot and Gross Rent Comparisons](https://github.com/EmilyBertani/Challenge_6/blob/main/Line_graph.png)

![Line Graph of Sale Price per Square Foot and Gross Rent Comparisons by Neighborood](https://github.com/EmilyBertani/Challenge_6/blob/main/Line_graph_widget_1.png)

![Line Graph of Sale Price per Square Foot and Gross Rent Comparisons by Neighborood](https://github.com/EmilyBertani/Challenge_6/blob/main/Line_graph_widget_2.png)

![Map View of San Francisco Comparing Sale Price per Square Foot and Gross Rent](https://github.com/EmilyBertani/Challenge_6/blob/main/Map_view.png)

---


## Contributors

Emily Bertani

Emily.Bertani.MD@gmail.com

[LinkedIn](https://www.linkedin.com/feed/)

---

## Licenses

MIT

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

