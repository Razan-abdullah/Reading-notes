# JupyterLab
---

 is a next-generation web-based user interface for Project Jupyter.



###  Jupyter lab usage : 

* JupyterLab enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner. For a demonstration of JupyterLab and its features, you can view this video:

* JupyterLab also offers a unified model for viewing and handling data formats. JupyterLab understands many file formats (images, CSV, JSON, Markdown, PDF, Vega, Vega-Lite, etc.) and can also display rich kernel output in these formats. See File and Output Formats for more information.


## Numpy 
---
stands for Numerical Python, is a library consisting of multidimensional array objects and a collection of routines for processing those arrays.

Using NumPy, mathematical and logical operations on arrays can be performed. This tutorial explains the basics of NumPy such as its architecture and environment. It also discusses the various array functions, types of indexing, etc. An introduction to Matplotlib is also provided. All this is explained with the help of examples for better understanding.

### Operations using NumPy

* Using NumPy, a developer can perform the following operations −

Mathematical and logical operations on arrays.

* Fourier transforms and routines for shape manipulation.

* Operations related to linear algebra. NumPy has in-built functions for linear algebra and random number generation.


## NumPy - Environment

---

Standard Python distribution doesn't come bundled with NumPy module. A lightweight alternative is to install NumPy using popular Python package installer, pip.

* To install NumPy, run the following command.

Python setup.py install

* To test whether NumPy module is properly installed, try to import it from Python prompt.

import numpy

* If it is not installed, the following error message will be displayed.

Traceback (most recent call last): 
   File "<pyshell#0>", line 1, in <module> 
      import numpy 
ImportError: No module named 'numpy'


---

## NumPy - Ndarray Object:


The most important object defined in NumPy is an N-dimensional array type called ndarray. It describes the collection of items of the same type. Items in the collection can be accessed using a zero-based index.

Every item in an ndarray takes the same size of block in the memory. Each element in ndarray is an object of data-type object (called dtype).
