# python3
basic calculator

a=int(input("enter first number :"))
b=int(input("enter second number :"))
operation=input("enter the operation :")
if operation=="+":
    print(f"addition of two number{a+b}")
elif operation=="-":
    print(f"subtration of two number{a-b}")
elif operation=="*":
    print(f"multiplicaton of two number{a*b}")
elif operation=="/":
    print(f"division of two number{a/b}")
else:
    print("not a basic operation")
