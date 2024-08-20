---

You can reshape an array in NumPy without altering its underlying data using functions like `np.reshape()`. 
This allows you to change the dimensions of an array while keeping the data intact. For example, if you have a one-dimensional array `a` and you want to transform it into a 2D array with 3 rows and 1 column, you can use `np.reshape(a, (3, 1))`. 
This operation rearranges the array elements into the new shape, providing a different view of the same data without copying or modifying the original array.
You can reshape an array without changing its data:

````python
c = np.reshape(a, (3, 1))
````
