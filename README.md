# csc522-character-biases
CSC522 Project - Gender and Race biases

This project Identifies Gender and Race biases in Audience Perception.
The data for the project is collected from [OpenPsychometrics.org](https://openpsychometrics.org/), enriched with [Betafaceapi.com](https://betafaceapi.com/) and is present inside the `data` directory.

## Notebooks

Some of the notebooks present in this repository:

* [Scraper](https://github.com/ncstate-csc522/character-biases/blob/main/Scraper.ipynb) - Used to fetch data from OpenPsychometrics, and save in the `data` directory.

* [PhotoLabels](https://github.com/ncstate-csc522/character-biases/blob/main/PhotoLabels.ipynb) - Scraper that uses Betafaceapi to add labels to the images downloaded from OpenPsychometrics

* [ImageLabeling](https://github.com/ncstate-csc522/character-biases/blob/main/ImageLabeling.ipynb) - Tool used to hand label gender/race on images.

* [EDA / EDA-OpenData](https://github.com/ncstate-csc522/character-biases/blob/main/EDA-OpenData.ipynb) - Exploration and Data Analysis documents, where we do parameter cleaning and joining them from both sources, and export into a single CSV. 

* [Cluster-Analysis](https://github.com/ncstate-csc522/character-biases/blob/main/Cluster-Analysis.ipynb) - Used to analyse possible clusters within the dataset, using unsupervised learning methods.

* [Model-Exploration-*](https://github.com/ncstate-csc522/character-biases/blob/main/Model-Exploration-OpenData.ipynb) - Gets exported data from *EDA*, executes and compares various classifiers with the hand labeled data with supervised learning methods. The most updated one is [Model-Exploration-OpenData](https://github.com/ncstate-csc522/character-biases/blob/main/Model-Exploration-OpenData.ipynb).


