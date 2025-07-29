Week Two Assignment Solution
Create an empty list called my_list

python
my_list = []
Append elements to my_list: 10, 20, 30, 40

python
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
Insert the value 15 at the second position in the list

python
my_list.insert(1, 15)  # Index 1 is the second position
Extend my_list with another list: [50, 60, 70]

python
my_list.extend([50, 60, 70])
Remove the last element from my_list

python
my_list.pop()  # Removes and returns the last item
Sort my_list in ascending order

python
my_list.sort()
Find and print the index of the value 30 in my_list

python
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
Complete Solution Code
Here's the complete code that accomplishes all tasks:

python
# 1. Create an empty list called my_list
my_list = []

# 2. Append elements to my_list: 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# 3. Insert the value 15 at the second position in the list
my_list.insert(1, 15)

# 4. Extend my_list with another list: [50, 60, 70]
my_list.extend([50, 60, 70])

# 5. Remove the last element from my_list
my_list.pop()

# 6. Sort my_list in ascending order
my_list.sort()

# 7. Find and print the index of the value 30 in my_list
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)

# Optional: Print the final list to verify all steps
print("Final list:", my_list)
