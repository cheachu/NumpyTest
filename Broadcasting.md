---

* Broadcasting in NumPy is a feature that enables you to perform operations on arrays of different shapes by automatically expanding the smaller array to match the dimensions of the larger one. For example, if you have a 2D array `a` and you want to add a 1D array with fewer elements, broadcasting allows you to do this efficiently.
* In the expression `a + np.array([1, 2, 3])`, the 1D array `[1, 2, 3]` is broadcast across the rows of the 2D array `a`. This means each element of the 1D array is added to the corresponding elements of each row of the 2D array, resulting in an element-wise addition that leverages the shape compatibility without the need for explicit loops or data replication.
  Example:

````python
result = a + np.array([1, 2, 3])
````
