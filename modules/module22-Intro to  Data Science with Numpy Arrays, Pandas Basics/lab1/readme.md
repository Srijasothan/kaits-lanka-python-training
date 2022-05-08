Aim:
A) Using a numpy module create an array and check the following:
1. Type of array 2. Axes of array
3. Shape of array 4. Type of elements in array


Program:
import numpy as np
arr=np.array([[1,2,3],[4,2,5]])
print("Array is of type:",type(arr))
print("no.of dimensions:",arr.ndim)
print("Shape of array:",arr.shape)
print("Size of array:",arr.size)
print("Array stores elements of type:",arr.dtype)