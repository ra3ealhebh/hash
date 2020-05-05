[عدل]from hashlib import *

def hash2(): print(""" 
\033[1;31m====================| 
	            \033[1;31m|
\033[1;33m1 :- md5 hash       \033[1;31m|
                    \033[1;31m| 
\033[1;33m2 :- sha1 hash      \033[1;31m|
                    \033[1;31m| 
\033[1;33m3 :- sha224 hash    \033[1;31m|
                    \033[1;31m| 
\033[1;33m4 :- sha256 hash    \033[1;31m|
                    \033[1;31m| 
\033[1;33m5 :- sha512 hash    \033[1;31m|
                    \033[1;31m| 
\033[1;33m0 :- exit           \033[1;31m|
		    \033[1;31m|
\033[1;31m====================| """) 
t = True
while t:
 hash2()
 inp = input ("Enter hash  number : ")
 if inp == ("1"):
  inp1 = input ("Enter your word : ") 
  x = md5(inp1.encode()).hexdigest() 
  print (" \033[1;33m your hash ====> "+x)
  exit = input("\033[1;31m Back to  Menu (y/n) : ") 
  if exit == "n":
   break 
 elif inp == "2":
  inp2 = input("Enter your word : ") 
  x1 = sha1(inp2.encode()).hexdigest() 
  print ("\033[1;33m your hash ====> " + x1) 
  exit = input("\033[1;31m Back to  Menu (y/n) : ") 
  if exit == "n":
   break 
 elif inp == "3": 
  inp3 = input("Enter your word : ") 
  x3 = sha224(inp3.encode()).hexdigest() 
  print ("\033[1;33m your hash ====> " + x3) 
  exit = input("\033[1;31m Back to  Menu (y/n) :  ") 
  if exit == "n":
   break 
 elif inp == "4": 
  inp4 = input("Enter your word : ") 
  x4 = sha256(inp4.encode()).hexdigest() 
  print (" \033[1;33m your hash ====> " + x4) 
  exit = input("\033[1;31m Back to  Menu (y/n) : ") 
  if exit == "n":
   break 
 elif inp == "5": 
  inp5 = input("Enter your word : ") 
  x5 = sha512(inp5.encode()).hexdigest() 
  print (" \033[1;33m your hash ====> " + x5) 
  exit = input("\033[1;31m Back to  Menu (y/n) : ") 
  if exit == "n":
   break
 elif inp == "0":
  exit()
