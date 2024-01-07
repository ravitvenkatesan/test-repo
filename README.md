# test-repo
## Initial test data
### Learning Github

### Creating an unordered list 
* unordered item list 1
* unordered item list 2

#Sample Questions
#Convert following np array to optimal data type(one that 
#requires least space)

import numpy as np
arr = np.array([1, 20, 300, 4000, 50000])
print(arr.dtype)
print(arr.nbytes)
arr = np.array([1, 20, 300, 4000, 50000], dtype='int32')
print(arr.dtype)
print(arr.nbytes)
arr = np.array([1, 20, 300, 4000, 50000], dtype='uint16')
print('uint16')
print(arr.dtype)
print(arr.nbytes)
print('for uint16', arr.astype(np.uint16))
print('int8', arr.astype(np.int8))
print('int16',arr.astype(np.int16))
print('int32', arr.astype(np.int32))
print(np.iinfo('int8'))
print(np.iinfo('int16'))
print(np.iinfo('int32'))
print(np.iinfo('int64'))
print(np.iinfo('uint16'))
print("*****************")
#Create np array that contains following tuples. What is the 
#difference between the two?
import numpy as np
T1 = [(1, 10, 10), (2, 20), (3, 30)]
T2 = [(1, 10), (2, 20), (3, 30)]
arr_t1 = np.array(T1, dtype='object')
arr_t2 = np.array(T2)
print(arr_t1)
print(arr_t1.shape)
print(arr_t2)
print(arr_t2.shape)
print(arr_t2.dtype)
print(arr_t2.nbytes)
arr_t2 = np.array([(1, 10), (2, 20), (3, 30)], dtype='int8')
print(arr_t2.dtype)
print(arr_t2.nbytes)
