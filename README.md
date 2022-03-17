# Even_Odd
numbers = (1, 2, 3, 4, 5, 6, 7, 8, 9, 10) # Declaring the tuple
print(numbers)
count_odd = 0
count_even = 0
for x in numbers:
        if not x % 2:
    	     count_even+=1
        else:
    	     count_odd+=1
print("Counting of Even Numbers :",count_even)
print("Counting of Odd Numbers :",count_odd)
