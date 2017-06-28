# Introduction to Data-Analysis with Pandas

## Follow-along tutorial PyData Berlin 2017

Pandas is the Swiss-Multipurpose Knife for Data Analysis in Python. With Pandas dealing with data-analysis is easy and simple but there are some things you need to get your head around first as Data-Frames and Data-Series. 

The tutorial provides a compact introduction to Pandas for beginners for I/O, data visualisation, statistical data analysis and aggregation within Jupiter notebooks.

### Installation

Having [Anaconda](https://www.continuum.io/downloads) installed simply create your ENV with 

```
# get this repository
git clone https://github.com/alanderex/pandas-pydata-berlin-2017

cd pandas-pydata-berlin-2017
# install working environment with conda
conda env create -n pandas-pydata-berlin-2017 -f environment.yml

# environment should be activated now
# if not type: source activate pandas-pydata-berlin-2017
# start juypter notebook
jupyter notebook
# paste the url displayed in your browser, looks like:
# http://localhost:8888/?token=fa08a1f56d3d0fbbdf7d07fec0c39cd471e06501f79a782a
``` 

![alt tag](pic/front.jpeg)

* reading and writing data across multiple formats (CSV, Excel, JSON, SQL, HTML,…)
    * CSV
    * JSON
    * HTML
    * Clipboard
    * EXCEL
* data
    * .info
    * .describe

* Selecting Data {from Paris Index talk with visualisation}
    * Colums
    * Rows
    * returns a copy // inplace
    * boolean indexing via visualisation | after selecting same order

* operations
    * add/substract
    * multiply
    * mention Index but don't go deep

* data visualisation
* work with built-in data visualisation

* statistical data analysis and aggregation.

* inner-mechanics of Pandas: Data-Frames, Data-Series & Numpy.

* working and making the most of indexes.

* how to mangle, reshape and pivot
