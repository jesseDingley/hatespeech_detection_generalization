# Detection of racism, sexism and hate speech in tweets with transformer-based models

Racism and Sexism are two sub-categories of Hate Speech. Racism, Sexism, and Hate Speech detection in a general sense are all problems that have been studied and revisited multiple times. In this work we try a new approach not studied before. We study the generalization of hate speech detection models. <b>Can a transformer-based general hate speech detection model perform as well as racism and sexism focused detection models on racism and sexism datasets?</b>. No.

This repository is split into multiple folders containing the code used for implementation and testing. Note that we do not provide the datasets in this repository.

 - 📁 <b>hatespeech_detection</b>: Contains:
    - `hatespeech-detection-data-bertweet.ipynb`: notebook containing the code for gathering and preprocessing hate speech data.
    - `hatespeech-detection-training.ipynb`: notebook containing the code for training the hate speech detection model.

 - 📁 <b>comparison</b>: Contains:
    - `hatespeech-detection-tests.ipynb`: notebook for testing the hate speech detection model on multiple datasets such as the racism and sexism test sets.


This work was accomplished by Jesse Dingley, Luca Melissari and Modar Sulaiman at University of Tartu.
