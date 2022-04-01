# Bielefeld University DL Course Project

This repo contains 3 code implementations for the Bielefeld University DL Course Project, 2 of them are for FashionMNIST Gan and 1 of them for pneumonia x-ray classification task.

The code used for this projects are based on this 2 repos;

-   GANs: https://github.com/eriklindernoren/PyTorch-GAN
-   X-ray: https://github.com/nateraw/huggingpics

### How to run

-   GANs: Just installing dependencies using requirements.txt and then running the .py files is enough, the data comes from pytorch itself and no additional downloads are needed.
-   X-ray: X-ray classification has a jupyter notebook in it and can be opened in Google Colab, data can be either uploaded manually or one can open up a Kaggle account and download data directly from Kaggle after creating an API key, how to do that is explained inside the notebook after uploading the kaggle.json file that has your API key in it all you have to do is to run all cells to have your model trained and validated.
