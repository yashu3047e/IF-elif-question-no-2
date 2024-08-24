# IF-elif-question-no-2
WAP to enter Total Bill amount and calculate discount as per given table and also calculate Net payable amount (total bill – discount) Total Bill Discount >=20000 15% of Total Bill

# This Code Has been written by yash
# IG handle - yshpvt
# no copyright 

name = input('Enter Your name : ')

a = float(input("Enter your total bill amount : "))
if a>=20000:
    discount = 0.15*a
    b = a - discount
    print(f"{name}, your Total Amount To Be Paid After 15% Discount : ",b)
    
elif a>=15000:
    discount1 = 0.10*a
    c = a - discount1
    print(f"{name}, your Total Amount To Be Paid After 10% Discount :", a - discount1)
    
elif a>=10000:
    discount2 = 0.05*a
    c = a - discount2
    print(f"{name}, your Total Amount To Be Paid After 5% Discount : ",c )
    
else:
    print(f"{name}, your Total Amount To Be Paid After Discount : ", a)
