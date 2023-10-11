


# Python Identify Operators



#(1) (is)
x=["apple","banana"]
y=["apple","banana"]
z=x

print(x is z)

# returns True because z is the same object as x

print(x is y)

"""returns False because x is not the the same object as y,
even if they have the same content"""

print(x==y)

""" to demonstrate the difference between "is" and "mm":
this comparsion returns True because x is equal to y """

#2) (is not)

x=["apple","banana"]
y=["apple","banana"]
z=x

print(x is not z)

# returns False because z is the same object as x

print(x is not y)

"""returns False because x is not the the same object as y,
even if they have the same content"""

print(x==y)

""" to demonstrate the difference between "is not" and "!mm":
this comparsion returns False because x is equal to y """


