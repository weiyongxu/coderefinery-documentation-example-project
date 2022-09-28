### Temperature analysis in spreadsheets

A python script for the analysis of temperatures in excel files.


### Why should I use this project ?

It makes it easy to analyse excel files with temperatures in them.


### Setup

You need `python>3.5` to run this script.

The project depends on the `pandas` library, install it with pip:
`pip install pandas`


### How to run?

You can run the script from the command-line using
```
python analyse_spreadsheet.py
```

You can use functions directly, for example: calculate the mean temperature of some data:
```python
from analyse_spreadsheet import mean_temperature

print(mean_temperature(data))
```


### How to cite this project?

Please email `training@esciencecenter.nl` to get instructions on how to properly cite this project.


### Contributing

You are welcome to contribute to the code via pull requests.  Please have a
look at the [NLeSC
guide](https://nlesc.gitbooks.io/guide/content/software/software_overview.html)
for guidelines about software development.
