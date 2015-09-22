# zdays15
## Text Mining - How to extract insights from text
To play around with Python use a Python Distribution
- Anaconda, Canopy, ... (https://wiki.python.org/moin/PythonDistributions)
- Manage dependencies with virtualenv (https://virtualenv.pypa.io/)
- first choice should be the Python Distribution package manager (e.g. conda) and then pip



### Data Pipeline steps
The goal is to build a Data Pipeline which extracts data and stores in Search Engine. A Data Pipelien could contain the following steps:
- data extraction - extract text from the different file format. 
    * data extraction with apache tika. Use [tika python](https://github.com/chrismattmann/tika-python) to extract text from different file formats
- [transform](unstructured_data.ipynb) - Transforming unstructured data into structured data.
- annotate data - use different strategies to annotate the text with metadata.
    * [annotate](annotate_data.ipynb) text with meta data from a external source.
    * [classify text](classify_text.ipynb) - annotate text with a supervised machine learning algorithm.
    * [cluserting text](clustering_text.ipynb) - annotate text with a unsupervised machine learning algorithm.
- store data
- visualize data