# File-Reading-and-Writing-
12.  File Reading and Writing 
import numpy as np
a1=np.array([[2,3],[4,5]])
np.savetxt("D:\\output.txt",a1,delimiter=",")
print("array save to outut.txt")
filename="D:\\output.txt"
data=np.loadtxt(filename,delimiter=",")
print(data)
Output:
array save to new.txt
[[2. 3.]
 [4. 5.]]
In text file:
2.000000000000000000e+00,3.000000000000000000e+00
4.000000000000000000e+00,5.000000000000000000e+00
