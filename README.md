# html-parser
A Jupyter Notebook implementing a parser for analysing HTML Articles 

The parser was developed as a requirement for applying in the MSc in Information Studies programme at the University of Amsterdam.

The goal was to parse a given collection of articles and plot its Word Count Distribution.

It is developed using only python packages and not 3rd-party ones.  
The parser implements [HTMLParser](https://docs.python.org/2/library/htmlparser.html).
[Counter](https://pypi.org/project/Counter/1.0.0/) package is used for counting words, [string](https://docs.python.org/3/library/string.html) for string manipulation & [matplotlib](https://matplotlib.org/index.html) for creating the histogram.