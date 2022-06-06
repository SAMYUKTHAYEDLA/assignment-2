

1.) What makes NumPy.shape() different from NumPy.size()?

NumPy.shape():- NumPy arrays have an attribute called shape that returns a tuple with each index having the number of corresponding elements

NumPy.size(): size() Function in Python. The size of an array is the total number of elements in the array. The NumPy.size() function in the NumPy package returns the size of a given array.

• Difference:- NumPy.shape() is used to get complete structural shape of our 2D array. For example (3,4). NumPy.size() will give us how many elements are present in total

2.) In NumPy, describe the idea of broadcasting

• The term broadcasting refers to the ability of NumPy to treat arrays of different shapes during arithmetic operations. Arithmetic operations on arrays are usually done on corresponding elements. If two arrays are of exactly the same shape, then these operations are smoothly performed

3.) What makes Python better than other libraries for numerical computation?

• Numerical Python has a fixed-size,

homogeneous (fixed-type), multi3.) What role does pandas play in data cleaning?

• Data cleaning with Pandas It is an essential skill of Data Scientists to be able to work with messy data, missing values, inconsistent, noise, or nonsensical data. To work smoothly python provides a built-in module Pandas.

4.) How do you use pandas to make a data frame out of n-dimensional arrays?

• import pandas as pd # Create the dataframe df = pd.DataFrame(numpy_array) df = pd.DataFrame(numpy_array, columns=['digits', 'words']) ... df = pd.DataFrame(numpy_array, index=['day1', 'day2', 'day3', 'day4'], columns=['digits', 'words'])

5.) Explain the notion of pandas plotting.

• Matplotlib is a Python plotting package that makes it simple to create two-dimensional plots from data stored in a variety of data structures including lists, numpy arrays, andstructures including lists, numpy arrays, and

pandas dataframes. Matplotlib uses an object oriented approach to plotting

Ex:- import pandas as pd

import matplotlib.pyplot as plt df = pd.read_csv('data.csv') plt.show()

df.plot()

FIL

Share

Extract Pages

Picture Sharing

PDF Annotation
