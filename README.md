
// Swapping best algorithms
1..*=== if a and b are the two variables we need to swap their values without third variable ===*
----
Lets Take two elements a and b for our better understanding
a=10
b=20

#a,b=b,a
#print("a= ",a,"b= ", b)# Using comma operators

#temp=b
#b=a
#a=temp
#print("a= ",a,"b= ", b)# Using third variable

#a=a+b
#b=a-b
#a=a-b
#print("a= ",a,"b= ", b)# Using +,- Operators

#a=a*b
#b=a/b
#a=a/b
#print("a= ",int(a),"b= ", int(b))# Using *,/ Operators

a=a^b
b=a^b
a=a^b
print("a= ",a,"b= ", b)# Using X-OR(^) Operator



-------= Program Performed on a list=---------
List = [1,22,42,42,52,55,634]
# Swapping the 1st element with last element

# ==== Method-1 Using Third-variable======
print("Before Swaping=",List)
temp = List[0]
List[0] = List[-1]
List[-1] = temp
print("After Swaping=",List)

# ===== Method-2 By position Inter-Changing ======
# print("Before Swaping=",List)
# List[0], List[-1] = List[-1], List[0]
# print("After Swaping=",List)

# ======= Method-3 Using X-OR(^) Operator
# print("Before Swaping=",List)
# List[0] = List[0]^List[-1]
# List[-1] = List[0]^List[-1]
# List[0] = List[0]^List[-1]
# print("After Swaping=",List)

# ======== Method-4 Using +,- Operators =====
# print("Before Swaping=",List)
# List[0] = List[0]+List[-1]
# List[-1] = List[0]-List[-1]
# List[0] = List[0]-List[-1]
# print("After Swaping=",List)

# ======== Method-5 Using *,/ Operators =====
# print("Before Swaping=",List)
# List[0] = List[0]*List[-1]
# List[-1] = List[0]/List[-1]
# List[0] = List[0]/List[-1]
# print("After Swaping=",List)
