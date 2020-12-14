# Words and sentences prediction
## Description

Real-time writing prediction and correction model based on the trie data structure, the Boyer-Moore algorithm for string matching, and the Levenshtein distance (using dynamic programming) for string similarity.

This was designed and implemented as the final project of the "Design and Analysis of Algorithms" and "Programming for Data Analysis" classes which are part of the [Master of Computer Systems](https://posgrados.iteso.mx/maestria-sistemas-computacionales) in the Western Institute of Technology and Higher Education [ITESO University](https://iteso.mx/).

## Usage

### Clone this repository

Clone this repository in your preferred path.

```python
git clone https://github.com/EarlOrlando/WordsSentencesPrediction.git
```

### Install dependencies

Install all Python dependencies. This project may work with other versions but this project has been tested only with the shown below.

```python
python -m pip install requests==2.25.0
python -m pip install pandas==1.1.5
python -m pip install numpy==1.19.3
python -m pip install bs4==4.9.3
python -m pip install nltk==3.5
python -m pip install matplotlib==3.3.3
```

## Execute Jupyter Notebook
By executing all the Jupyter notebook cells the example GUI is run.

File `sentences.csv` stores all the pages acquired from [Wikipedia en Español](https://es.wikipedia.org/wiki/Wikipedia_en_espa%C3%B1ol) so these are not downloaded on every execution. This file has to be removed in order to download new Wikipedia examples.

File `Crea_total.zip` contains the Spanish language words corpus acquired from [Corpus de Referencia del Español Actual (CREA)](http://corpus.rae.es/lfrecuencias.html).