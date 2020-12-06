# Mushroom-Image-Classification
---
## Overview
---
## Project Goals
---
The goal of this project is to be able to verify the classification of various edible mushrooms collected by harvesters through a computer vision model. Another goal is for this model to provide good distinction between these edible mushrooms and their poisonous look-a-likes.
## Motivation and Background
---
A restaurant has dealt with buying incorrectly classified mushrooms from a local harvester. The manager wants to implement a round of mushroom identification checking, so the restaurant isn't completely trusting the harvesters classification, but rather verifying it. However, since none of the staff has any experience in identifying mushrooms, and it isn't viable to hire a mushroom specialist long term, the manager has hired our Data Science firm to build a computer vision model to sort through harvested mushrooms and independently verify their classification. I sometimes harvest wild edible mushrooms in my spare time and have worked as a manager and chef for a restaurant in the past, so I was a natural choice for a Data Scientist to work on this project.
## Data
---
This project uses a data set from [a github user](https://github.com/bechtle/mushroomobser-dataset). The author has written code to scrape images from [mushroom observer](https://mushroomobserver.org/), which contains user contributed images of mushrooms by species. I used images previously scraped by the author for this project found on a [dropbox link](https://www.dropbox.com/sh/m1o91dwd1nto6w0/AADACdc0WF_oIAyKN5W1UvDta/images_files/complete_dataset/TRAIN_2006-2015?dl=0&subfolder_nav_tracking=1) from user contributions between 2006 and 2015. I chose to study the following specific mushroom species: Amanita Muscaria (Fly Agaric), Russula Mariae (Mary Russula), Boletus Edulis (Penny Bun), Cantharellus (Chanterelle), Amanita Bisporigera (Destroying Angel), and Omphalotus Olearius (Jack-O-Lantern). In total there are 2,818 images. After containing these images in a zip file, they take up 55.1 MB of space.
## Repository Navigation
---
<pre>
Data               : <a href=https://www.kaggle.com/harperd17/mushroom-pictures-sorted>Data Kaggle Upload </a>
Code               : <a href=https://github.com/harperd17/Mushroom-Image-Classification/blob/master/Notebooks/Modeling%20Code.ipynb>Modeling Notebook </a>
                   : <a href= insert link>Google Colab Notebook Link </a>
Report             : <a href=https://github.com/harperd17/Mushroom-Image-Classification/blob/master/Report/Report%20Notebook.ipynb>Report Notebook</a>
</pre>
## Project Information
---
<b>Author: </b>David Harper <br>
<b>Language: </b>Python <br>
<b>Tools/IDE: </b>Anaconda and Google Colab <br>
<b>Libraries: </b>keras, tensorflow, scikit-learn, numpy, pandas, plotly, matplotlib, zipfile, os, shutil, errno, PIL, and random
