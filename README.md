Method1:-
total = 0 
# creating a list
list1 = [11, 5, 17, 18, 23] 
# Iterate each element in list
# and add them in variable total
for ele in range(0, len(list1)):
    total = total + list1[ele]
 # printing total value
print("Sum of all elements in given list: ", total)
Method 2:-
total = 0
ele = 0 
# creating a list
list1 = [11, 5, 17, 18, 23]
# Iterate each element in list
# and add them in variable total
while(ele < len(list1)):
    total = total + list1[ele]
    ele += 1
# printing total value
print("Sum of all elements in given list: ", total)
Method 3:-
numbers = [1,2,3,4,5,1,4,5]
# start parameter is not provided
Sum = sum(numbers)
print(Sum)
 # start = 10
Sum = sum(numbers, 10)
print(Sum)
