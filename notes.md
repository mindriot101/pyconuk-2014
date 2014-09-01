# Studying astronomy at the University of Warwick, with Python

## Responses

### Danny

Simon,

This could be fun. I don't have a particularly interesting use, but I think its impressive how widely used Python is within the science community. For me it means I rarely need to code in another language, as one can do almost everything in python. Reducing data, fitting models, making plots etc. Astropy might be worth a mention unless there is representation for it specifically. It looks to me to be the most organised and active astronomy specific Python module.

Danny

### Tom

hi simon,

not sure they are particularly interesting but examples from me are:

* use of python to run MCMC chains, with interfaces written in C++ for the parts that need to run fast (I have 2 or 3 examples of this)

* python programmes to carry out maximum entropy-based Doppler imaging, again with heavy lifting implemented in C++

* python interface to allow easy access to ULTRACAM data

tom

## Topics

* Exoplanets
  * NGTS
    * building the pipeline
      * reducing images
        * `multiprocessing`
      * coordinating tasks
        * `subprocess`
    * data analysis
* Explosions in the distant universe
  * fitting SEDs
    * `scipy.optimize`
* White dwarfs
* Instrumentation
  * Wrapping ULTRACAM code
* Modelling
  * Maximum entropy Doppler imaging
* General
  * ability to start with raw data and end with visualisations
  * wrapping C for speed

## Packages

* emcee
* numpy
* matplotlib
* scipy
