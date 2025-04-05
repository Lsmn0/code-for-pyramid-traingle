# code for pyramid traingle
n = int(input("Enter the number: "))
i = 0
while i < n:
    i +=1 # if you don't put i+=1 or i = i + 1 iterate then it will be infinite loops
    print(" "*(n-i), end=" ")
    print("*"*(2*i-1),end=" ")
    print()
