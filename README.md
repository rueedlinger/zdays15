# zdays15
## Text Mining - How to extract insights from text
To play around with Python use a Python Distribution
- Anaconda, Canopy, ... (https://wiki.python.org/moin/PythonDistributions)
- Manage dependencies with virtualenv (https://virtualenv.pypa.io/)
- first choice should be the Python Distribution package manager (e.g. conda) and then pip


### Data Pipeline steps
The goal is to build a Data Pipeline which extracts data and stores in Search Engine. 
- data extraction - extract text from the different file format. (eg. use [tika python](https://github.com/chrismattmann/tika-python))
- [transform](unstructured_data.ipynb) - Transforming unstructured data into structured data.
- annotate data with with machine learing or meta data from external sources. 
    * [annotate](annotate_data.ipynb) with meta data. 
    * [classify text](classify_text.ipynb)
    * [cluserting text](clustering_text.ipynb)
- store data
- visualize data