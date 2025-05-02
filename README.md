# Skip-Gram
Training Model with converting words to vector and Skip-Gram 

## Tech :hammer_and_wrench: Languages and Tools :

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original.svg" title="Jupyter Notebook" alt="Jupyter Notebook" width="40" height="40"/>&nbsp;
  <img src="https://assets.st-note.com/img/1670632589167-x9aAV8lmnH.png" title="Google Colab" alt="Google Colab" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/psf/requests/master/ext/requests-logo.png" title="Request" alt="Request" width="40" height="40"/>&nbsp;
  <img src="https://avatars.githubusercontent.com/u/83768144?s=200&v=4"  title="Polars" alt="Polars" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original.svg" title="Numpy" alt="Numpy" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/matplotlib/matplotlib-original.svg"  title="MatPlotLib" alt="MatPlotLib" width="40" height="40"/>&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/en/b/b1/Gensim_logo.png"  title="Gensim" alt="Gensim" width="40" height="40"/>&nbsp;
</div>

- Python : Popular language for implementing Neural Network
- Jupyter Notebook : Best tool for running python cell by cell
- Google Colab : Best Space for running Jupyter Notebook with hosted server
- Requests : Simple HTTP library for accessing APIs and websites
- Polars : Fast DataFrame library for efficient data processing
- Numpy : Best Library for working with arrays in python
- MatPlotLib : Library for showing the charts in python
- Gensim : Predefined model for converting words to vectors

## Run the Notebook on Google Colab

You can easily run this code on google colab by just clicking this badge [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AsadiAhmad/Skip-Gram/blob/main/Code/Skip_Gram.ipynb)

## Dataset

This dataset named `LISA` and i modified them into three files (easy for working) :

- Documents.txt (Documents are stored here)
- Queries.txt (Queries are stored here)
- Result.txt (Real related results are stored here)

### Download Dataset
you can use this modified Dataset with clicking this badges :

Documents : [![Static Badge](https://img.shields.io/badge/Documents-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/TF-IDF-Model/blob/main/Dataset/Documents.txt)

Queries : [![Static Badge](https://img.shields.io/badge/Queries-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/TF-IDF-Model/blob/main/Dataset/Queries.txt)

Result : [![Static Badge](https://img.shields.io/badge/Result-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/TF-IDF-Model/blob/main/Dataset/Result.txt)

or Download the raw dataset :

Raw Dataset : [![Static Badge](https://img.shields.io/badge/Raw-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://ir.dcs.gla.ac.uk/resources/test_collections/lisa/)

### Frames of Dataset
Here is part of the Documents raw text :

<div display=flex align=center>
  <img src="/Pictures/4.PNG" width="600px"/>
</div>

Here is part of the Queries raw text :

<div display=flex align=center>
  <img src="/Pictures/5.PNG" width="600px"/>
</div>

Here is part of the Real Result raw text :

<div display=flex align=center>
  <img src="/Pictures/6.PNG" width="600px"/>
</div>

Here is part of the Documents frame :

<div display=flex align=center>
  <img src="/Pictures/1.PNG" width="600px"/>
</div>


Here is part of the Queries frame :

<div display=flex align=center>
  <img src="/Pictures/2.PNG" width="600px"/>
</div>


Here is part of the Real Result frame :

<div display=flex align=center>
  <img src="/Pictures/3.PNG" width="600px"/>
</div>

## PreProcess

- Clear garbage charachters and digits
- Lower all alphabet charachters
- Tokenization
- Word Counting
- Show Zipf Law
- Calculate stop and steⅿⅿing words
- Remove stop and steⅿⅿing words

<div display=flex align=center>
  <img src="/Pictures/8.PNG"/>
</div>

## Result

<div display=flex align=center>
  <img src="/Pictures/7.png" width="600px"/>
</div>

## License

This project is licensed under the MIT License.
