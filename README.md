# python_assignment-3
numbers = (1, 2, 3, 4, 5, 6, 7, 8, 9)                             #sample input: (1, 2, 3, 4, 5, 6, 7, 8, 9)
count_odd = 0
count_even = 0                                                    # Expected output: Number of even numbers : 4
for x in numbers:                                                 #                  Number of odd numbers : 5
    if x%2== 0:
        count_even += 1
    else:
        count_odd +=1
print("Number of even numbers :", count_even)                     # My output: Number of even numbers : 4
print("Number of odd numbers :", count_odd)                       #            Number of odd numbers : 5
