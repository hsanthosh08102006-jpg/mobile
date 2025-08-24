# mobile
import numpy as np

# Create an array
x = np.array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
print("Original array (x):", x)

# Slicing the array
# Get elements from index 2 to 5 (exclusive)
slice1 = x[2:5]
print("Slice from index 2 to 5:", slice1)

# Get all elements from index 4 to the end
slice2 = x[4:]
print("Slice from index 4 to the end:", slice2)

# Get elements with a step
slice3 = x[::2]
print("Elements with a step of 2:", slice3)

# Reshaping the array
# The total number of elements must remain the same
reshaped_matrix = x.reshape(2, 5)
print("\nReshaped into a 2x5 matrix:\n", reshaped_matrix)
