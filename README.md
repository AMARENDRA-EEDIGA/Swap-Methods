
#Swapping Technics---
Lets Take two elements a and b for our better understanding
a=10
b=20

# Using comma operators
#a,b=b,a
#print("a= ",a,"b= ", b)

# Using third variable
#temp=b
#b=a
#a=temp
#print("a= ",a,"b= ", b)

# Using +,- Operators
#a=a+b
#b=a-b
#a=a-b
#print("a= ",a,"b= ", b)

# Using *,/ Operators
#a=a*b
#b=a/b
#a=a/b
#print("a= ",int(a),"b= ", int(b))

# Using X-OR(^) Operator
a=a^b
b=a^b
a=a^b
print("a= ",a,"b= ", b)




# Swap the 1st element with last element in a List
*-------= Program Performed on a list=---------*<br>
List = [1,22,42,42,52,55,634]
# ==== Method-1 Using Third-variable======
print("Before Swaping=",List) <br>
temp = List[0] <br>
List[0] = List[-1] <br>
List[-1] = temp <br>
print("After Swaping=",List) <br>

# ===== Method-2 By position Inter-Changing ======
print("Before Swaping=",List)<br>
List[0], List[-1] = List[-1], List[0] <br>
print("After Swaping=",List) <br>

# ======= Method-3 Using X-OR(^) Operator
print("Before Swaping=",List) <br>
List[0] = List[0]^List[-1]<br>
List[-1] = List[0]^List[-1]<br>
List[0] = List[0]^List[-1]<br>
print("After Swaping=",List)<br>

# ======== Method-4 Using +,- Operators =====
print("Before Swaping=",List)<br>
List[0] = List[0]+List[-1]<br>
List[-1] = List[0]-List[-1]<br>
List[0] = List[0]-List[-1]<br>
print("After Swaping=",List)<br>

# ======== Method-5 Using *,/ Operators =====
print("Before Swaping=",List)<br>
List[0] = List[0]*List[-1]<br>
List[-1] = List[0]/List[-1]<br>
List[0] = List[0]/List[-1]<br>
print("After Swaping=",List)<br>
