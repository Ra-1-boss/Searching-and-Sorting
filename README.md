# Searching
def linear_search(arr, target):
    for i in range(len(arr)):
        if arr[i] == target:
            return i
    return -1

# Example
data = [3, 7, 2, 9, 5]
print(linear_search(data, 9))  # Output: 3 (index)
