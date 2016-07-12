#Naive Bees

**Identifying Honey Bees: Image Processing and Machine Learning**



Using almost 4000 images taken from beespotter.org, can we help scientists to 
identify Apis(Honey bee) or Bombus(Bumble bee). This will be my first foray into image processing. 
  
**Motivation:** Being such important pollinators and the source of honey, it's important to help protect the dwindling population of bees in anyway we can.


Ultimately was able to correctly discern honey or bumblebee with 69.95% accuracy. 
_________________

##Tools

* Pandas
* Numpy
* scipy
* skimage
* seaborn

_________________

##Lets Get Down to Beesiness

* [Experimenting with image preprocessing and filters](./bees/Untitled.ipynb)
* [Extracting RGB color channels, additional preprocessing, creating image feature matrix](./bees/BeeNaive.ipynbYCnbps/Untitled.ipynb)

_________________

##Limitations  

Due to the vast amount of information (every pixel of an image is basically a feature!), things would occassionally not be able to run within memory. Even after reducing feature space with Principle Component Analysis.

__________________

##Presentation  

* [Slides](./presentation/mcnulty_NaiveBeesChallenge_MZ.pdf)