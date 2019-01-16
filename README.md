Real Estate Price Prediction for Belgian Municipalities
-----------------------

This project will predict the yearly real estate price for the Belgian municipalities<br>
If you only wish to view the final result, you can open the [Jupyter notebook](https://notebooks.azure.com/alexbraila/projects/RealEstate/html/Real%20Estate%20Price%20Prediction%20for%20Belgian%20Municipalities.ipynb), otherwise, you can install everything locally by following the below instructions

Installation
----------------------

### Download the data

* Clone this repo to your computer
* Get into the folder using `cd belgian-real-estate`
* Run `mkdir data`
* Switch into the `data` directory using `cd data`
* Download the data files into the `data` directory from STATBEL
   	* [here](https://statbel.fgov.be/fr/open-data?category=66), files Ventes de biens immobiliers par commune selon la nature du bien dans le plan cadastral (1980-1989) through (2010-2017)
	* [here](https://statbel.fgov.be/fr/themes/population/structure-de-la-population#figures), file Population de droit par commune au 1 janvier (2011-2018)
    * [here](https://statbel.fgov.be/fr/open-data?category=178), file Statistique fiscale des revenus 2005-2016
* Switch back into the `belgian-real-estate` directory using `cd ..`

### Install the requirements
 
* Install Anaconda
* Install the requirements using `pip install -r requirements.txt`
    * Make sure you use Python 3

Usage
-----------------------

* Launch the Jupyter Notebook App and start the notebook `Real Estate Price Prediction for Belgian Municipalities.ipynb`
* Run the whole notebook