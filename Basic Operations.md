* In NumPy, array operations are designed to be both efficient and expressive.
* Element-wise operations allow you to perform arithmetic directly on arrays. 
* For instance, `a + b` adds corresponding elements of arrays `a` and `b`, and `a * b` multiplies each element of `a` with the corresponding element of `b`. 
* These operations are performed element-wise across the arrays. For matrix multiplication, NumPy provides the `a.dot(b)` method, which computes the dot product of arrays `a` and `b`. 
* This operation follows linear algebra rules and is used for more complex matrix multiplications. 
* Together, these operations enable straightforward and efficient manipulation of numerical data in arrays.

Perform basic arithmetic operations on arrays:

````python
a + b    # Element-wise addition
a * b    # Element-wise multiplication
a.dot(b) # Matrix multiplication
````
