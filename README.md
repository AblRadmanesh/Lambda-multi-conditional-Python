# Lambda-multi-conditional
Definition of several conditions in lambda
If you need to create several conditions within the hidden function (lambda) you can do this:

x=lambda A,B:print(f"{print(True) if A=='first condition'else print(False)} {print(True if B=='second condition'else print(False)}")
x("first condition","second")
