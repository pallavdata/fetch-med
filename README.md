# Pubmed-Paper-Fetcher-and-Processor

**Research tools** - ChatGPT https://chatgpt.com/, Stackoverflow http://stackoverflow.com/

**External Tools**- 
- requests → To send and receive data
- deep-translator → To translate
- bs4 & lxml → To parse XML
- pandas → To save data in .csv and .xlsx file
- openpyxl → Data to .xlsx converting engine.

`Tested on Python version 3.8 and 3.13`
*(Package Supports python -V 3.8 or higher)*


*This package is designed for searching the PubMed database and retrieving data, including the paper’s ID, title, publication date, non-academic authors, and their metadata.*

INSTALL:

`pip install -i https://test.pypi.org/simple/ fetch-med`

**WITH** command-line syntax:
--

|  Syntax   |     |
|-----|-----|
| -h,--help   | show this help message and exit   |
| -d,--debug   | debug the program   |
| -q,--query   | query to get papers   |
| -f,--file   | path of the output file   |
| --force   | force article to be added even if author is not present   |
| -g,--get   | max number of articles to be present in output. By default all   |
| -c,--count   | max number of articles to fetch and parse. By default all   |
| -e,--ext   | supports: .json, .csv and .xlsx   |

<!-- - -h,--help  : show this help message and exit
- -d,--debug : debug the program
- -q,--query : query to get papers
- -f,--file  : path of the output file
- --force    : force article to be added even if author is not present
- -g,--get   : max number of articles to be present in output. By default all
- -c,--count : max number of articles to fetch and parse. By default all
- -e,--ext   : supports: .json, .csv and .xlsx -->

For Example:

`get-papers-list --debug --query covid-19 --force -c 2 -g 1`

**WITHOUT** command-line syntax:
--
Run: `get-papers-list`


_____
Note :
- *If no file or incorrect file path is given then output will be printed on console*
- *Dont include -e or --ext to run the program or it will give you list of supported extensions*



