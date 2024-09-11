# str-predefined-functions

1) capitalize()
--------------------------------------------------------------------------------------------------------------------------------
=>This Function is used for capitalizing the first letter First word of a given Sentence only.
=>Syntax:      strobj.capitalize()
				(OR)
			strobj=strobj.capitalize()
-----------------
Examples:
-----------------
>>> s="python"
>>> print(s,type(s))-------------------python <class 'str'>
>>> s.capitalize()--------------------'Python'

2) title():
--------------------------------------------------------------------------------------------------------------------------------
=>This is used for obtaining Title Case of a Given Sentence  (OR) Making all words First 
    Letters are capital.
Syntax:          s.title()
			(OR)
			s=s.title()



3) index()
--------------------------------------------------------------------------------------------------------------------------------
=>This Function obtains Index of the specified Value
=>If the specified value does not exist then we get ValueError
=>Syntax:        strobj.index(Value)
=>Syntax:	indexvalue=strobj.index(value)



4) upper()
--------------------------------------------------------------------------------------------------------------------------------
=>It is used for converting any type of Str Data into Upper Case.
=>Syntax:-   strobj.upper()
			OR
			strobj=strobj.upper()



5) lower()
--------------------------------------------------------------------------------------------------------------------------------
=>It is used for converting any type of Str Data into lower Case.
=>Syntax:-   strobj.lower()
			OR
			strobj=strobj.lower()



6)  isupper()
--------------------------------------------------------------------------------------------------------------------------------
=>This Function returns True provided the given str object data is purely Upper Case otherwise it returns False.
Syntax:     strobj.isupper()




7)islower()
--------------------------------------------------------------------------------------------------------------------------------
=>This Function returns True provided the given str object data is purely lower Case otherwise it returns False.
	Syntax:     strobj.islower()




8) isalpha()
--------------------------------------------------------------------------------------------------------------------------------
=>This Function returns True provided str object contains Purely Alphabets otherwise returns False.

		Syntax:   strobj.isalpha()





9) isdigit()
--------------------------------------------------------------------------------------------------------------------------------
=>This Function returns True provided given str object contains purely digits otherwise returns False
Examples:
--------------------
>>> s="python"
>>> s.isdigit()------------------False
>>> s="python123"
>>> s.isdigit()----------------False
>>> s="123"
>>> s.isdigit()-----------------True



10) isalnum()
--------------------------------------------------------------------------------------------------------------------------------
=>This Function returns True provided str object contains either Alpabets OR Numerics or Alpha-Numerics only otherwise It returns False.
	=>Syntax:   strobj. isalphanum()



 11) isspace()
-------------------------------------------------------------------------------------------------------------------------------
=>This Function returns True provided str obj contains purely space otherwise it returns False.
=>Syntax:    strobj.isspace()



12) split()
-------------------------------------------------------------------------------------------------------------------------------
=>This Function is used for splitting the given str object data into different words base specified delimter ( -  _  # % ^ ^ , ; ....etc)
=>The dafeult deleimter is space 
=>The Function returns Splitting data in the form of list object
=>Syntax:    strobj.split("Delimter")
				(OR)
			strobj.split()
				(OR)
			listobj=  strobj.split("Delimter")
				(OR)
			listobj=strobj.split()




13) join():
-------------------------------------------------------------------------------
=>This Function is used for combining or joining list of values from any Iterable object
=>Syntax:    strobj.join(Iterableobject)





14) startswith():
----------------------
=>The startswith() Function returns True if the string starts with the specified value, otherwise False.





15) endswith():
----------------------
=>The endswith() Function returns True if the string ends with the specified value, otherwise False.



16) swapcase()
----------------------------
=>Make the lower case letters upper case and the upper case letters lower case:
Examples:
>>>s="PyThOn"
>>>s.swapcase()--------pYtHoN
>>>




15. lstrip()
16  rstrip()
17. strip()


