# Data-structure-program-10arr = []

n = int(input("Enter number of elements: "))
for i in range(n):
    arr.append(int(input()))

print("List:", arr)

# Insertion
x = int(input("Enter element to insert: "))
arr.append(x)
print("After insertion:", arr)

# Deletion
d = int(input("Enter element to delete: "))
if d in arr:
    arr.remove(d)
    print("After deletion:", arr)
else:
    print("Element not found")

# Searching
s = int(input("Enter element to search: "))
if s in arr:
    print("Element found")
else:
    print("Element not found")
