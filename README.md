# Project-8
#  Program 8: WAP to create a list of only the even integer appearing in the input list(may have elements of other types) using for loop and list comprehension.
def cubes():
newlist=[]
number=[1,2,3,4,5,6,"seven"]
for i in number: if type(i)==int:
if i % 2==0:
newlist.append(i**3)
print(newlist)
cubes()
