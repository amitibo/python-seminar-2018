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

Copyright (c) IBM Research Haifa

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

The Matplotlib examples in the "Advanced Python Seminar" notebook are
Copyright (c) 2012-2013 Matplotlib Development Team; All Rights Reserved.

The "SeattleCycling" notebook is based on a [post](http://jakevdp.github.io/blog/2015/07/23/learning-seattles-work-habits-from-bicycle-counts/) by Jake VanderPlas in his
blog [Pythonic Perambulations](http://jakevdp.github.io). The contents of the [Pythonic Perambulations](http://jakevdp.github.io)
blog are released under the [MIT license](https://opensource.org/licenses/MIT).
