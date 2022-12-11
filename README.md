# Musical Chord Classification

- EE541 Project (Fall 2022)
- Group 19
- Creator: [Lifuling Wei](https://github.com/llling339), [Jacqueline Liu](https://github.com/Jacqueline45)

There are four notebooks in this repository, which you can run in Google Colab (no dependency issues) as long as dataset path is correctly specified:

1. MusicalChord.ipynb
This notebook mostly followed this [Kaggle Post](https://www.kaggle.com/code/ahmetcelik158/mathematics-of-music-chord-classification/notebook), in which you can see detailed data processing, feature analysis and generation, and the results of Random Forest Classifiers.

2. MusicalChord-MLP.ipynb
This notebook contains the model definition of MLP, dataloader, and detailed training and evaulation processes and results.

3. MusicalChord-GRU.ipynb
This notebook is very similar to 2. except that the model is changed to GRU.

4. MusicalChord-XGBoost.ipynb
This notebook shows how we implemented XGBoost and the corresponding results.