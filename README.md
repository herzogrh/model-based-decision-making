# River modeling: Gelderland
This is the corresponding GitHub repository to the EPA1323 Model-Based Decision Making Class in the academic year of 2019/2020 of TU Delft. 

## Introduction

The Netherlands, in order to keep their citizens safe and their land from flooding, are in a constant battle against nature. The River Ijssel, stemming from the Rhine, flows through the provinces of Gelderland and Overijssel before entering the Ijsselmeer. In the coming years, flood risk is expected to increase and measures have to be taken now. However, deep uncertainty revolves around the possible floodings that could occur and which measures work best in terms of expected casualties, damages, evacuation costs and investment costs. The present code focusses on exploring possible policies for the province of Gelderland. For further background and problem framing information, please get in touch and request the final report of the reseach conducted. 

### Source

The source code this project was based on stems from Jan Kwakkel's [GitHub repository](https://github.com/quaquel/epa1361_open/tree/master/final%20assignment). 

### Authors

- Ignasi Cortés Arbués
- Francesco Cruz Torres
- Rico Herzog
- Samuel Timmers
- Ashok Willis


## How-To

### Main Results

The main results obtained from this analysis can be found in several Jupyter Notebooks in the `model` folder:

1. `1 - Open Exploration.ipynb`: This notebook shows the results of an open exploration approach of the model
2. `2 - Multi-Scenario MORDM Gelderland.ipynb`: This notebook shows the results of a Multi-Scenario MORDM approach run on a problem formulation tailored to the province of Gelderland.
3. `3 - Multi-Scenario MORDM Overijssel.ipynb`: This notebook shows the results of a Multi-Scenario MORDM approach run on a problem formulation tailored to the province of Overijssel.
4. `4 - Multi-Scenario MORDM Holistic View.ipynb`: This notebook shows the results of a Multi-Scenario MORDM approach run on a problem formulation trying to optimize overall outcomes for both provinces.
5. `5 - Sensitivity Analysis.ipynb`: This notebook shows the results of a sensitivity analysis using OLS-Regression and SOBOL to discover possible leverages in negotiations.

### Directory structure

```
---\
    model\
    ------ *Model files, forked from quaquel/epa1361_open*
    ------ 1 - Open Exploration.ipynb
    ------ 2 - Multi-Scenario MORDM Gelderland.ipynb
    ------ 3 - Multi-Scenario MORDM Overijssel.ipynb
    ------ 4 - Multi-Scenario MORDM Holistic View.ipynb
    ------ 5 - Global Sensitivity Analysis.ipynb

    results\
    ------ *Modeling outputs to reproduce results*

    figures\
    ------ *Figures saved from the notebooks*
```

To reproduce our results, please look into the `requirements.txt` file. 

