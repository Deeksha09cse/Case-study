# Case-study
# Python program to calculate total cost of 3 different items and add a discount of 10% if the total exceeds 50.
a=int(input())
b=int(input())
c=int(input())
total=a+b+c
if(total>=50):
  discount=total-(total*10/100)
  print(discount)
else:
  print(total)
