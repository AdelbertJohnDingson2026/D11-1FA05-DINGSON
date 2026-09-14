# D11-1FA05-DINGSON
import math

# Step 1: Get user input for the two points
x1 = float(input("Enter x1: "))
y1 = float(input("Enter y1: "))
x2 = float(input("Enter x2: "))
y2 = float(input("Enter y2: "))

# Step 2: Calculate the distance using the Euclidean formula
# Using pow() to square the differences and sqrt() to find the square root
distance = math.sqrt(math.pow(x2 - x1, 2) + math.pow(y2 - y1, 2))

# Step 3: Display the results clearly
print(f"The distance between the two points is: {distance:.2f}")


# ==========================================
# REFLECTION AND EVALUATION
# ==========================================
# Using a library is more practical than writing calculations from scratch because it provides pre-tested, highly accurate functions that save development time. 
# In this activity, instead of manually implementing complex algorithms to approximate square roots, I could simply call math.sqrt() and math.pow(). 
# This kept the code clean, reduced the chances of mathematical errors, and let m
