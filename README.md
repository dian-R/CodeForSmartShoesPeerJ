# Code for SmartShoes paper
This repository contains code for data generation and the Machine Learning part of the smart shoes project. It also contain code for result analysing.

## Contents of the repository
* **automatedAnalysis.py** - library defining functions for reading data from experiments, extract features and perform the ML step (learning, evaluating and progressive feature removal). Can evaluate multiple sensor configurations in parallel, up to the maximum number of threads availalble.
* **FiguresRerun.ipynb** - jupyter notebook containing code for the analysis of Mechine Learning results and figure plotting.

## Prerequisites
Python 3 (>= 3.6)

Jupyter notebook

## Gettig Start
* Clone the repository.
* Clone the raw foot pressure data.
* Prepare two dirctory, one for result of different window size, another one for result of different configuration and feature numbers.
* Run the code in the terminal from the directory of **automatedAnalysis.py** 

```bash
python3 automatedAnalysis.py /DIR/foot_pressure_raw_data/ /DIR/result_of_different_configs/ /DIR/result_of_different_window_size/ 
```
* Run **FiguresRerun.ipynb** in jupyter notebook to generate reusult and figures.

## Versioning

