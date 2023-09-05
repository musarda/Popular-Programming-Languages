Adding and Subtracting Matrices in Python

```py
# Input matrices
matrix1 = [[1, 2], [3, 4]]
matrix2 = [[4, 5], [6, 7]]

# Printing elements of matrix1
print("Printing elements of first matrix")
for row in matrix1:
	for element in row:
		print(element, end=" ")
	print()

# Printing elements of matrix2
print("Printing elements of second matrix")
for row in matrix2:
	for element in row:
		print(element, end=" ")
	print()

# Subtracting two matrices
result = [[0, 0], [0, 0]]
for i in range(len(matrix1)):
	for j in range(len(matrix1[0])):
		result[i][j] = matrix1[i][j] - matrix2[i][j]

# Printing the result
print("Subtraction of two matrix")
for row in result:
	for element in row:
		print(element, end=" ")
	print()

```