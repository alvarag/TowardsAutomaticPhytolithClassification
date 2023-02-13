# Towards automatic phytolith classification using feature extraction and combination strategies

This repository presents a comparative analysis of the use of different types of sets of features, combination of features, and combination of classifiers (through Stacking) for automatic phytolith classification, including the novel vision transformers that have shown a remarkable performance in different areas, including computer vision.
In this research, twenty-two different sets of features (three based on shape, sixteen on appearance, and three on texture) and six classifiers (alone and combined via stacking strategies) were compared.

## Authors
- José-Francisco Díez-Pastor
- Pedro Latorre-Carmona
- Álvar Arnaiz-González
- Antonio Canepa Oneto
- Javier Ruiz-Pérez
- Débora Zurro

## Citation policy
The code was implemented by Jose-Francisco Díez-Pastor.

### Cite this software as:
_Under review_

## Phytoliths images
The images are in the [repository of the Pompeu Fabra University](https://repositori.upf.edu/handle/10230/44939).

## Notebooks and files
- [01_Vision_Transformers_classification.ipynb](https://github.com/alvarag/TowardsAutomaticPhytolithClassification/blob/main/01_Vision_Transformers_classification.ipynb): Notebook to train and assess the Vision Transformers, directly using the pytholiths' images, for training.
- [02_Dataset_generation_and_experiments_execution.ipynb](https://github.com/alvarag/TowardsAutomaticPhytolithClassification/blob/main/02_Dataset_generation_and_experiments_execution.ipynb): Notebook to create the datasets with all the strategies used in the paper and then perform the experiments with all the models.
- [03_Analyze_results.ipynb](https://github.com/alvarag/TowardsAutomaticPhytolithClassification/blob/main/03_Analyze_results.ipynb): Notebook to analyze the results created by the previous ones.

![Pipeline](https://github.com/alvarag/TowardsAutomaticPhytolithClassification/blob/main/Phytolith%20pipeline.png)
