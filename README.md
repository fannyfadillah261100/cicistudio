# cicistudio
contoh pembuatan repository
import numpy  as np
x = np.arange(15, dtype=np.int64).reshape(3, 5)
x[1:, ::2] = -99
array([[  0,   1,   2,   3,   4],
#        [-99,   6, -99,   8, -99],
#        [-99,  11, -99,  13, -99]])

x.max(axis=1)
# array([ 4,  8, 13])

