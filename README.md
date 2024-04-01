# Clone-Structured Cognitive Graphs


[![DOI](https://zenodo.org/badge/344697858.svg)](https://zenodo.org/badge/latestdoi/344697858)

Code for ["Learning cognitive maps as structured graphs for vicarious evaluation"](https://www.biorxiv.org/content/10.1101/864421v4.full)

[Check out the interactive version in Colab!](https://colab.research.google.com/drive/1Mvznx8sc4OVZvpiy9VY2yeb-Df-jxKZC?usp=sharing)

### CHANGELOG
Changes made by @acolasn (anconi.1999@gmail.com)

>I change the standard for early stopping, so  that when we  are learning the transition  matrixand we enable early  stopping, it doesnot stop if the last loss was lower than the current loss, but  allows some fluctuations by making the current loss not lower than any of the past five losses. 