
# About This Project

In this project, I want to Classify Data from Stellar Classification Dataset using Supervised Classification Algorithms (https://www.kaggle.com/fedesoriano/stellar-classification-dataset-sdss17). In astronomy, stellar classification is the classification of stars based on their spectral characteristics. The classification scheme of galaxies, quasars, and stars is one of the most fundamental in astronomy. The early cataloguing of stars and their distribution in the sky has led to the understanding that they make up our own galaxy and, following the distinction that Andromeda was a separate galaxy to our own, numerous galaxies began to be surveyed as more powerful telescopes were built. This datasat aims to classificate stars, galaxies, and quasars based on their spectral characteristics.


## Content of The Dataset

The data consists of **100,000 observations of space taken by the SDSS (Sloan Digital Sky Survey)**. Every observation is described by 17 feature columns and 1 class column which identifies it to be either a star, galaxy or quasar.

* **obj_ID** = Object Identifier, the unique value that identifies the object in the image catalog used by the CAS
* **alpha** = Right Ascension angle (at J2000 epoch)
* **delta** = Declination angle (at J2000 epoch)
* **u** = Ultraviolet filter in the photometric system
* **g** = Green filter in the photometric system
* **r** = Red filter in the photometric system
* **i** = Near Infrared filter in the photometric system
* **z** = Infrared filter in the photometric system
* **run_ID** = Run Number used to identify the specific scan
* **rereun_ID** = Rerun Number to specify how the image was processed
* **cam_col** = Camera column to identify the scanline within the run
* **field_ID** = Field number to identify each field
* **spec_obj_ID** = Unique ID used for optical spectroscopic objects (this means that 2 different observations with the same spec_obj_ID must share the output class)
* **class** = object class (galaxy, star or quasar object)
* **redshift** = redshift value based on the increase in wavelength
* **plate** = plate ID, identifies each plate in SDSS
* **MJD** = Modified Julian Date, used to indicate when a given piece of SDSS data was taken
* **fiber_ID** = fiber ID that identifies the fiber that pointed the light at the focal plane in each observation

## Related Stacks

* **Numpy** : https://numpy.org/
* **Pandas** : https://pandas.pydata.org/
* **Seaborn** : https://seaborn.pydata.org/
* **Matplotlib** : https://matplotlib.org/
* **Scikit-learn** : https://scikit-learn.org/stable/
* **XGBoost** : https://xgboost.readthedocs.io/en/stable/

## Feedback

If you have any feedback, please reach out to us at vitorihaldijiran14@gmail.com


