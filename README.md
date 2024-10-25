# NLP : Video games genre multi-class classification

## About the project

This work was done for my final project of Natural Language Processing (Språkteknologi) course of Umeå University - Sweden.

The goal of this project was to analyze video games dataset and try to see if from their description, its possible to find the game genre.

<u>Research question:</u> **Can we build a text classification model that accurately categorizes a game into its genre based on its description?**

## Original dataset

Found on kaggle.com - [93182 Steam games](https://www.kaggle.com/datasets/joebeachcapital/top-1000-steam-games?select=93182_steam_games.csv)

## Content

- `data/` :
  - `93182_steam_games.csv`: Original dataset (to [download](#original-dataset))
  - `steam_games_reduced.csv`: Preprocessed data without *Removing common words* appliyed.
  - `steam_games_reduced_2.csv`: Preprocessed data with all the steps.
- `preprocessing.ipynb` : Contains all the preprocessing steps as 
  - Data filtering, 
  - Tokenzation & morphological operations,
  - Removing common words.
- `train_evaluate.ipynb` : Contains all the training & evalution steps
  - Vectorization,
  - Training,
  - Evaluation.

## Credits

Made by Louis VRAIE