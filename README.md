# iOS_Reverse_Engineering

**How to reverse engineer Objective-C methods (class or instance method).**

We use **FRIDA** for dynamic analysis & **IDA PRO** for static analysis.

FRIDA
How to reverse a method? \n
First you need to attach FRIDA to a targeted process \n
"Add code here"
Get the targeted method address
"Add code here"
print out the arguments
"Add code here"
print out the return value
"Add code here"

IDA Pro
 Extracting the dyld shared cashes library from the iOS frameware
 After getting the dyld you should Extracting the .dylip file where the method leave.

 After we have the dylip file, we are ready to throw it to IDA Pro 
