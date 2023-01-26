# matrixmultiplicationinpython

# matrix 3x3
matrix1=[[1,2,3],[1,2,3],[1,2,3]]
# matrix 3x4
matrix2=[[1,2,3,4],[1,2,3,4],[1,2,3,4]]
# result 3x4
result=[[0,0,0,0],[0,0,0,0],[0,0,0,0]]

for i in range(len(matrix1)):
    for j in range(len(matrix2[0])):
        for k in range(len(matrix2)):
            result[i][j]+= matrix1[i][k] * matrix2[k][j]
            
            
            
            
result            
