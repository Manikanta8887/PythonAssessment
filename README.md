# PythonAssessment
PythonAssessment


# 1st

# units = int(input("Enter the number"))

# fixedcharge = 50

# def currentbill(units,fixedcharge):
#     if(units<=100):
#        bill = fixedcharge+units*5
#        return bill
#     elif(units>100 and units<=200):
#        bill = fixedcharge+units*7
#        return bill
#     else:
#        bill = fixedcharge+units*10
#        return bill
   
# receipt=currentbill(units,fixedcharge)
# print(receipt)

# 2nd

# num1 = int(input("Enter the number1: "))
# num2 = int(input("Enter the number2: "))
# num3 = int(input("Enter the number3: "))

# def greatestnumber(num1,num2,num3):
#     if(num1>num2 and num1>num3):
#        return (num1,"num1 is greater than num2 and num3")
#     elif(num2>num1 and num2>num3):
#        return (num2,"num2 is greater than num1 and num3")
#     else:
#        return (num3,"num3 is greater than num1 and num2")
   
# result=greatestnumber(num1,num2,num3)
# print(result)

#  3rd
# type = (input("Choose the number for addtion 1,for subtraction 2,for multiplication 3, for division 4 or to end the code please enter ENDCODE"))

# while (type!="ENDCODE"):
#     num1=int(input("Enter the number1 : "))
#     num2=int(input("Enter the number2 : "))

#     def arithmeticoperations(type,num1,num2):
#         if(type=="1"):
#             add = num1 + num2
#             return add
#         elif(type=="2"):
#             sub = num1 - num2
#             return sub
#         elif(type=="3"):
#             multiply = num1 * num2
#             return multiply
#         elif(type=="4"):
#             div = num1 // num2
#             return div
#         else:
#             return ("Please enter the valid number")
   
#     result=arithmeticoperations(type,num1,num2)
#     print(result)
    
# 4th
# def factorial_iterative(n):
#     if n < 0:
#         return "Factorial not for negative numbers."
#     result = 1
#     for i in range(1, n + 1):
#         result *= i
#     return result

# print(factorial_iterative(5))  

# 5th
# n = int(input("Enter the number of terms: "))

# a, b = 0, 1
# print("Fibonacci sequence:")
# for i in range(n):
#     print(a, end=" ")
#     a, b = b, a + b

#6th

# for i in range(1, 101):
#     if i % 3 == 0 and i % 5 == 0:
#         print(i, "fizzbuzz")
#     elif i % 3 == 0:
#         print(i, "fizz")
#     elif i % 5 == 0:
#         print(i, "buzz")


#7th
# num1=int(input("enter the number: "))
# for i in range(1,num1+1):
#     if(num1 % i == 0):
#         print("the divisors are ", i)

#8th
# num1 = int(input("Enter the number: "))

# res = 0 
# while num1 > 0:
#     rev = num1 % 10  
#     count=+rev
#     res = res * 10 + rev  
   
#     num1 = num1 // 10  

# print("Reversed Number:", res)
# print(count)
