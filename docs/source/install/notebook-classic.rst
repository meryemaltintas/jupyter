import numpy as np

# 2x2 defining a matrix
A = np.array([[1, 2], [3, 4]])
print("Matris A:\n", A)
------------------------------------
B = np.array([[5, 6], [7, 8]])

# adding matrix
C = A + B
print("A + B:\n", C)
---------------------------
# matrix multiplication
D = np.dot(A, B)
print("A * B (Matrix multiplication):\n", D)
