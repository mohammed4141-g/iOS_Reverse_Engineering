# iOS_Reverse_Engineering

**How to reverse engineer Objective-C/Swift methods (class or instance method).**

We use **FRIDA** for dynamic analysis & **IDA PRO** for static analysis.

we will use simple program as example "link to the Mach-O executable".

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


 Binary diffing with IDA Pro


<h3>⚡ Quick Commands</h3>

<pre><code>
# iOS Reverse Engineering
frida -U -f com.example.app

# VRadar Scanner
python scanner.py --target 192.168.1.1
</code></pre>

<h1>
  <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="40" height="40"/> 
  Hey! Nice to see you.
</h1>
