# PythonW1

print("1 -Add")
print("2 - Multiply")
print("3 - Subtract")
print("4 - Divide")
option = int (input("choose an operation"))

if(option in[1,2,3,4,5,6,7,8,9]):
    num1 = int(input("enter first number: "))
    num2 = int(input("enter second number: "))

if(option ==1):
    result = num1 + num2
elif(option ==2):
   result = num1 * num2
elif(option ==3):
   result = num1 - num2
elif(option ==4):
   result = num1 // num2  

else:
    print("invalid selection selected")

print("The resul of the operation is {}" .format(result))
