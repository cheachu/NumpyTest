---

To save NumPy arrays to files, you can use the `np.save()` function. This function stores arrays in a binary format with a `.npy` file extension. For example, `np.save('array_file.npy', array)` saves the array `array` to a file named `array_file.npy`. This format preserves the array's shape, data type, and contents, making it easy to reload later.
Save a NumPy array to a file:

````python
np.save('array.npy', a)
````
