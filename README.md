# plotLineChart
This is a tool to help users to generate line chart for their data.

It is implemented by Python and using plotly library.
This program will read a input file (input.csv defaultly) and generate a line chart for it.

*** Installation ***
You have to install Python (3.6+) and plotly in order to execute this program.

1. Install Python 3.6 or later.
   https://www.python.org/downloads/

2. Install plotly
   pip install plotly
   
Official site:
Python https://www.python.org
plotly https://plot.ly/python/

*** Usage ***
python plot.py [<filename>]
The filename specifies the name of input file. The default filename is input.csv if you don't supply this argument.

e.g.
python plot.py ==> read input.csv to generate line chart
python plot.py <input file> ==> read the input file to generate line chart

Executing snapshot:
D:\chart>python plot.py
* input file:input.csv
* chart title:HOCL 300X
* y title:HCOO-CL(counts/10s)
* x title:Times (sec)
* number of dataset: 3
* label of dataset:['Times (sec)', 'Cat 1', 'Cat 2']
* drawing the line chart...
* line chart done
