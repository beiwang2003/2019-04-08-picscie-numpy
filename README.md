# High-Performance Python and Interoperability with Compiled Code

   * [347 Lewis Library, Vis Lab](https://www.google.com/maps?q=Lewis+Library,+Princeton,+NJ+08540&pws=0)
   * April 8‒10, 2019
   * 9:30am‒12:00pm
   * On the [Princeton Research Computing website](https://researchcomputing.princeton.edu/events/high-performance-python-and-interoperability-compiled-code-48-410)

## Abstract

Python is a notoriously slow language, so why is it widely used by scientists and machine learning experts? In a numerically heavy task, an interpreted, dynamically typed environment can the hundreds to thousands of times slower than a compiled, statically typed one, which can make the difference between minutes of waiting and days of waiting, or between coarse models on small datasets and fine-grained models on large datasets. The trick is to drive compiled functions from the interpreted command line, as is done in R, and to frame your problem in array programming primitives, as is done in Matlab, but in a general-purpose language with hundreds of thousands of extensions to glue to every conceivable interface.

In this three day workshop from April 8th-10th we will examine the numerical processing ecosystem that has grown up around Python. The key library in this ecosystem is Numpy, which enables fast array programming and also provides a common data structure for sharing large, numerical datasets. We will walk through the process of restructuring "for loop" algorithms as "columnar" algorithms based on Numpy, as well as using Numba to speed up "for loop" algorithms by compiling the Python code. We'll do the same on a GPU using CuPy (a Numpy clone written for GPUs) and Numba. We'll also explore methods of mixing Python and C++, both for performance and for compatibility with existing libraries. Finally, I'll introduce Pandas as a convenient front-end to Numpy for data analysis.

## Instructions

Participants are strongly encouraged to bring a laptop to work through exercises. We will use conda and pip-in-conda, so superuser ("sudo") permissions are not required. Participants should have a good general working knowledge of Python and a little C++ (enough to understand the discussion of Python-C++ bindings).

Come with conda ([Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://docs.anaconda.com/anaconda/install/)) for Python 3 installed on your laptop or on a system you can access. Make sure you can install Numpy, Numba, Pandas, and JupyterLab. You will not be required to install GPU libraries or have access to a GPU. All of the exercises will be conducted in JupyterLab. No prior knowledge of these libraries will be assumed.