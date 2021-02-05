# tpw-questions1-5
#1

print("Jake Raju")
print("56 chicken piece drive")
print("Thornhill, Ontario")
print("Canada".format())

#2

name = input("Type your name: ")
print(f"Hello, {name}.")

#3

length = float(input("enter the length(m): "))
width = float(input("enter the width(m): "))
area = (length * width)
print(f"the area of the room is {area} meters squared")

#4

length = float(input("enter length of the field(f): "))
width = float(input("enter width of the field(f): "))
area = length * width
print(f"the area of the field is {area} feet")

#5 

bottle1 = float(input("how many 1L or less bottles: "))
bottle2 = float(input("how many more than 1L bottles: "))
bottle1 *= .1
bottle2 *= .25
refund = bottle1 + bottle2

print("refund: $%.1f." % refund)
