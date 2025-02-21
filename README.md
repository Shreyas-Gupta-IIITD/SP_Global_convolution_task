# SP_Global_convolution_task

The repository contains ***solution written from scratch*** for Homework Task given during the SPGI-R2 interview. 

## Problem Statement: 
Write python code to apply convolution operation on a image of size (100 x 100 x 3) with kernel size of (3 x 3) in broadcasting manner. Can have dynamic padding, stride for the convolution operation.

Note: can only use `Numpy`, refer the implementation of Scipy convolution operation, avoid For loops


### Proposed Solution :
Refer the code provided in above file.

Why use np.as_strided ?
It enables us to get a new view of an existing array without copying data so suitable for sliding window operations like convolution without explicitly using any loops.
