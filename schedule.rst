Python for Physicists - Lausanne, Feb 2013
==========================================

:Author: Valentin Haenel <valentin@haenel.co>
:Course Date: 11-15 Feb 2013
:Link: http://physique.cuso.ch/cours/3cycle/detail-cours/item/courses/python-1s

Schedule
--------

.. contents::

Day 1 - Morning
...............

* Welcome

  * Introduction and motivation
  * Presentation of outline
  * Survey of skill-level/experience
  * Material: (`PDF Slides
    <https://github.com/pcp13/orga/blob/master/materials/haenel-introduction-2013-02-pcp13.1.pdf?raw=true>`_, `Sources <https://github.com/pcp13/intro>`_)

* System Installation

  * Installing Python on your system

* Ipython -- the advanced Python shell

  * Help system, magic functions, aliases, history and tabs
  * Using alternative interfaces, QTConsole and IPYNotebook

  * Material: Chapter 1.1.3 of the Python Scientific Lecture Notes (`HTML <http://scipy-lectures.github.com/intro/intro.html#the-interactive-workflow-ipython-and-a-text-editor>`_)
  * `IPython Notebook Demo <https://github.com/pcp13/ipynb-demo>`_

* Basic Python

  * Basic syntax and type system
  * Lists and dictionaries
  * Control flow and list comprehensions
  * Functions, classes and modules
  * Exception handling

  * Material: Chapter 1.2 of the Python Scientific Lecture Notes
    (`HTML <http://scipy-lectures.github.com/intro/language/python_language.html>`_)
  * Exercises are included in the lecture notes
  * `Solutions <https://github.com/scipy-lectures/scipy-lecture-notes/tree/master/intro/solutions>`_

Day 1 - Afternoon
.................

* Software Carpentry

  * Best practices
  * Development methodologies
  * Zen of Python
  * Material: `PDF Slides <https://github.com/pcp13/orga/blob/master/materials/haenel-best-practices-talk-slides-2013-02-Lausanne.pdf>`_, `Sources <https://github.com/pcp13/best-practices-talk>`_

Day 2 - Morning
...............

* Testing

  * The merits of writing tests
  * The unittest library
  * Alternatives: nosetest, doctest
  * Materials: `PDF Slides
    <https://github.com/pcp13/orga/blob/master/materials/haenel-testing-talk-2013-02-pcp13.1.pdf?raw=true>`_, `Sources <https://github.com/pcp13/testing-talk>`_
  * Exercises and solutions are available from a `Git repository <https://github.com/pcp13/testing-exercises>`_

* Version Control with git

  * Basic command set
  * Description of the Git storage model
  * Interacting with remote repositories
  * Examples of github usage
  * Materials: `PDF Slides <https://github.com/pcp13/orga/blob/master/materials/haenel-git-talk-4d92601.pdf?raw=true>`_
  * Exercises are at the end of the slides

Day 2 - Afternoon
.................

* Numpy -- the fast array container

  * Basic arrays, dtypes and operations
  * Indexing, reshaping and slicing
  * Copies, views and fancy indexing
  * Materials: Chapter 1.3 of the Python Scientific Lecture Notes (`HTML
    <http://scipy-lectures.github.com/intro/numpy/index.html>`_)
  * Exercises are included in the lecture notes
  * `Solutions <https://github.com/scipy-lectures/scipy-lecture-notes/tree/master/intro/solutions>`_

Day 3 - Morning
...............

* Scipy -- the scientific algorithm collection

  * File input/output: scipy.io
  * Special functions: scipy.special
  * Linear algebra operations: scipy.linalg
  * Fast Fourier transforms: scipy.fftpack
  * Optimization and fit: scipy.optimize
  * Statistics and random numbers: scipy.stats
  * Interpolation: scipy.interpolate
  * Numerical integration: scipy.integrate
  * Signal processing: scipy.signal

  * Material: Chapter 1.5 of the Python Scientific Lecture Notes (`HTML <http://scipy-lectures.github.com/intro/scipy.html>`_)
  * Exercises are part of the lecture notes
  * `Solutions <https://github.com/scipy-lectures/scipy-lecture-notes/tree/master/intro/solutions>`_

  

Day 3 - Afternoon
.................

* Matplotlib -- scientific plotting

  * Basic plotting
  * Customizing lines, points, labels, axes, titles
  * Advice for publication quality plots
  * Alternative plotting libraries, Chaco, Bokeh
  * Material: Chapter 1.4 of the Python Scientific Lecture Notes (`HTML <http://scipy-lectures.github.com/intro/matplotlib/matplotlib.html>`_)

Day 4 - Morning
...............

* Parallelization -- when a single thread is not enough

  * multiprocessing
  * concurrency with IPython
  * message passing with mpi4py
  * Materials: `PDF Slides <https://github.com/pcp13/orga/blob/master/materials/haenel-parallel-talk-2013-02-pcp13.1-1-gd423122.pdf?raw=true>`_, `Sources <https://github.com/pcp13/parallel-talk>`_
  * Exercises, but unfortunately no solutions, are available from a `Git repository <https://github.com/pcp13/parallel-exercises>`_

Day 4 - Afternoon
.................

* Interfacing with C/C++ -- if you need external libraries

  * Python C-API
  * Ctypes
  * Swig
  * Cython
  * Material: Chapter 2.12 of the Python Scientific Lecture Notes (`HTML <http://scipy-lectures.github.com/advanced/interfacing_with_c/interfacing_with_c.html>`_)

* Numpy internals, the ndarray structure


Day 5 - Morning
...............

* Debugging, Profiling and Optimization

  * The Python debugger
  * The Python profiler
  * Viewing and analysing the profiler output
  * Useful optimizations
  * Material: Chapters 2.3 and 2.4 of the Python Scientific Lecture Notes (`HTML <http://scipy-lectures.github.com/advanced/debugging/index.html>`_ and `HTML <http://scipy-lectures.github.com/advanced/optimizing/index.html>`_)

* Scientific Data Storage -- load and save your data

  * Pickle, cPickle, NPY/NPZ
  * Interfacing with Databases
  * HDF5 with PyTables
  * Using compression
  * Material: `PDF Slides
    <https://github.com/pcp13/orga/blob/master/materials/haenel-data-storage-2013-02-pcp13.1.pdf?raw=true>`_, `Sources <https://github.com/pcp13/data-storage-talk>`_

Day 5 - Afternoon
.................

* Examination

* An outlook towards other useful packages

  * numexpr
  * Joblib
  * Starcluster
  * PiCloud
  * scikits-learn
  * MDP
  * scikits-image
  * Pandas
  * Sympy
  * Wakari
  * Blaze
  * Numba
  * Open-Opt
  * Differential Equations and FEM
  * Theano
