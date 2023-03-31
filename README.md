# squares

1.Write a Python function that takes in a list of numbers and returns the sum of the squares of all the numbers in the list.
A.test_list = [3, 5, 7, 9, 11]
 
# printing original list

print("The original list is : " + str(test_list))
 
 
# sum of squares

res = 0

for i in test_list:

    from math import pow

    res += pow(i, 2)

res = int(res)
# printing result

print("The sum of squares of list is : " + str(res))
