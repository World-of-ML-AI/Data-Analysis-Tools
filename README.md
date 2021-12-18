# Data-Analysis-Tools

A data scientist must be a good data analyzer also. This repository contains Jupyter Notebooks for all the tools one need to perform Data Analysis such that Numpy, Pandas, Matplotlib, Seaborn and also some sample case studies are also included. We have included Exploratory Data Analysis on very famous datasets like the IPL Matches Dataset, Superheroes Dataset, FIFA Players Dataset from Kaggle and also Iris Dataset by University Of California, Irvine Machine Learning Repository.

## Numpy
![Numpy](https://raw.githubusercontent.com/lionelsamrat10/Data-Analysis-Tools/main/Images/numpy.png)

[Notebook Available here](https://github.com/lionelsamrat10/Data-Analysis-Tools/blob/main/Numpy/Numpy%20complete%20Tutorial.ipynb)

<p>
NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.
</p>

### What is NumPy?

At the core of the NumPy package, is the ndarray object. This encapsulates n-dimensional arrays of homogeneous data types, with many operations being performed in compiled code for performance. There are several important differences between NumPy arrays and the standard Python sequences:

* NumPy arrays have a fixed size at creation, unlike Python lists (which can grow dynamically). Changing the size of an ndarray will create a new array and delete the original.

* The elements in a NumPy array are all required to be of the same data type, and thus will be the same size in memory. The exception: one can have arrays of (Python, including NumPy) objects, thereby allowing for arrays of different sized elements.

* NumPy arrays facilitate advanced mathematical and other types of operations on large numbers of data. Typically, such operations are executed more efficiently and with less code than is possible using Python’s built-in sequences.

* A growing plethora of scientific and mathematical Python-based packages are using NumPy arrays; though these typically support Python-sequence input, they convert such input to NumPy arrays prior to processing, and they often output NumPy arrays. In other words, in order to efficiently use much (perhaps even most) of today’s scientific/mathematical Python-based software, just knowing how to use Python’s built-in sequence types is insufficient - one also needs to know how to use NumPy arrays.
