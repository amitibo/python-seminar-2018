# Intro session to data science with Python 

This repo contains the notebooks used during the second part
of the "Intro session to data science with Python".

## Setup Environment

To run the notebooks on your computer, clone the repository. It
is recommended to create a conda environment using the  included **environment.yml** file:
```sh
$ git clone git@github.ibm.com:AMITAID/python_advanced_seminar.git
$ cd python_advanced_seminar
$ conda env create -f environment.yml
```

Hopefully everything goes well and you can start the notebooks by running
the following:

```sh
$ conda activate rise
$ cd notebooks
$ jupyter notebook
```

## Presentation Mode

To display in presentation mode, follow the instructions to install and activate the [RISE](https://github.com/damianavila/RISE) extension.

License
----

Copyright (c) 2018 IBM Research Haifa

Licensed under the MIT License (MIT)

The Matplotlib examples in the "Advanced Python Seminar" notebook are
Copyright (c) 2012-2013 Matplotlib Development Team; All Rights Reserved.

The "SeattleCycling" notebook is based on a [post](http://jakevdp.github.io/blog/2015/07/23/learning-seattles-work-habits-from-bicycle-counts/) by Jake VanderPlas in his
blog [Pythonic Perambulations](http://jakevdp.github.io). The contents of the [Pythonic Perambulations](http://jakevdp.github.io)
blog are released under the [MIT license](https://opensource.org/licenses/MIT).
