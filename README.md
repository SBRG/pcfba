# pcfba

Python code for the macromolecular resource allocation module of BENG213 and *FBAfd*.
Includes methods for constraint-based modeling and extending them to account for proteome allocation.


Author: Laurence Yang
- Department of Bioengineering, UCSD
- Systems Biology Research Group

## Installation
---
1. Download the repository:
`git clone https://github.com/SBRG/pcfba.git`

2. Then run
`python setup.py develop`

3. Install [jupyter notebook](http://jupyter.readthedocs.io/en/latest/install.html).

Now you can run the notebooks in examples/


Required python packages:
- python (2.7 and up. Tested mostly on 2.7)
- cobrapy
	- tested on 0.5.11
	- modifications might be needed for versions >= 0.6
- pandas
- numpy
- scipy
- matplotlib
- seaborn
- (optional) sklearn

---
## Content

| Description | Notebook |
|-----|----------------|
  |  Growth rate | [growth_rate_pcfba_R02.ipynb](https://github.com/SBRG/pcfba/blob/master/examples/growth_rate_pcfba_R02.ipynb) |
  |  Substrate uptake hierarchy | [complex_media_R02.ipynb](https://github.com/SBRG/pcfba/blob/master/examples/complex_media_R02.ipynb)   |
 |  Predicting proteome allocation | [proteomics.ipynb](https://github.com/SBRG/pcfba/blob/master/examples/lecture12/proteomics.ipynb) |
