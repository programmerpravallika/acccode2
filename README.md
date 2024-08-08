'''Hari wants to buy a t-shirt, he checked in different shopping accounts. He observed that the different types of discounts on that t-shirt in various shopping accounts.He want to buy the t-shirt with low cost. He asked you to find the cheapest account to buy a t shirt.'''
print("flipcart")
a=int(input("enter the price of t-shirt:"))
b=int(input("enter the discount of t-shirt:"))
c=int(input("enter the shipping charges of t-shirt:"))
print("snapdeel")
d=int(input("enter the price of t-shirt:"))
e=int(input("enter the discount of t-shirt:"))
f=int(input("enter the shipping charges of t-shirt:"))
print("amazon")
g=int(input("enter the price of t-shirt:"))
h=int(input("enter the discount of t-shirt:"))
i=int(input("enter the shipping charges of t-shirt:"))
A=a*b/100
B=a-A+c
D=d*e/100
E=d-D+f
G=g*h/100
H=g-G+i
if(E>B and H>B):
    print("flipcart is cheapest ")
if(B>E and H>E):
    print("snapdeel is cheapest ")
else:
    print("amazon is cheapest ")
