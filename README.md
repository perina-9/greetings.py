python assignment 2
# Step 1: Create an empty list called MY_LIST
MY_LIST = []

# Step 2: Append the elements 10, 20, 30, 40
MY_LIST.append(10)
MY_LIST.append(20)
MY_LIST.append(30)
MY_LIST.append(40)

# Step 3: Insert the value 15 at the second position (index 1)
MY_LIST.insert(1, 15)

# Step 4: Extend MY_LIST with another list [50, 60, 70]
MY_LIST.extend([50, 60, 70])

# Step 5: Remove the last element from MY_LIST
MY_LIST.pop()

# Step 6: Sort MY_LIST in ascending order
MY_LIST.sort()

# Step 7: Find and print the index of the value 30
index_of_30 = MY_LIST.index(30)
print("Final List:", MY_LIST)
print("Index of 30:", index_of_30)
