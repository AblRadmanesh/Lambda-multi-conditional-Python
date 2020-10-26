# Lambda-multi-conditional
<p align= "center"><img src="http://s16.picofile.com/file/8411888634/Python_Lambda_1280x720.png" width="450px" height="300px">
  
  
Definition of several conditions in lambda
If you need to create several conditions within the hidden function (lambda) you can do this:

x=lambda A,B:print(f"{print(True) if A=='first condition'else print(False)} {print(True) if B=='second condition'else print(False)}")
x("first condition","second")

<p align= "center"><img src="http://s16.picofile.com/file/8411890300/lambda_output.png">
