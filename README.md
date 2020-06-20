# Python
### Identity Operators 
### These operators compare the memory location of two objects
### it is possible to find out whether 2 variables pointing to the same object or not

### Identity Operators are
###  is ---> both objects are the same 
###  is not --> if both objects are different

a=25
b=25

if (a is b):
    print(" both variables are refering the same object")
else:
     print(" both variables have different object")

print(id(a))        
print("ID of a =", id(a))
print("ID of b =", id(b))

b=26
if (a is b):
    print(" both variables are refering the same object")
else:
     print(" both variables have different objects")

### Note: Id() can we use to find out object id.

print("ID of a =", id(a))
print("ID of b =", id(b))
