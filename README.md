# Phython-Assigmemt-8


Open In Colab
In [ ]:
#Write a Python program to calculate the length of a string.
def string_length(str1):
    count = 0
    for char in str1:
        count += 1
    return count
print(string_length('Dhanush roy'))
11
In [ ]:
#Write a Python program to count the number of characters (character frequency) in a string.
def char_frequency(str1):
    dict = {}
    for n in str1:
        keys = dict.keys()
        if n in keys:
            dict[n] += 1
        else:
            dict[n] = 1
    return dict
print(char_frequency('google.com'))
{'g': 2, 'o': 3, 'l': 1, 'e': 1, '.': 1, 'c': 1, 'm': 1}
In [ ]:
#Python program to count no:of times letter “o” appears in string=”hello world”
count = 0
  
for i in test_str: 
    if i == 'e': 
        count = count + 1
  
# printing result  
print ("Count of e in GeeksforGeeks is : "
                            +  str(count))
---------------------------------------------------------------------------
NameError                                 Traceback (most recent call last)
<ipython-input-5-0e9e1a84e7bf> in <module>()
      2 count = 0
      3 
----> 4 for i in test_str:
      5     if i == 'e':
      6         count = count + 1

NameError: name 'test_str' is not defined
In [ ]:
#script that takes input from the user and displays that input back in upper and lower cases
user_input = input("What's your favourite language? ")
print("My favourite language is ", user_input.upper())
print("My favourite language is ", user_input.lower())
What's your favourite language? english
My favourite language is  ENGLISH
My favourite language is  english
In [ ]:
#Python program to count occurrences of a substring in a string.
str1 = 'The quick brown fox jumps over the lazy dog.'
print()
print(str1.count("fox"))
print()
1

In [ ]:
#Python program to compare two strings
print("Enter 'x' for exit.")
string1 = input("Enter first string: ")
if string1 == 'x':
    exit();
else:
    string2 = input("Enter second string: ")
    if string1 == string2:
        print("\nBoth strings are equal to each other.")
        print(string1,"==",string2);
    else:
        print("\nStrings are not equal.")
        print(string1,"!=",string2);
Enter 'x' for exit.
Enter first string: hi
Enter second string: hi

Both strings are equal to each other.
hi == hi
In [9]:
#Python program to perform Deletion of a character 
s = input("enter the string:")
print(s.replace('a', ''))
enter the string:bangalore
bnglore
In [10]:
#program to print every character of a string entered by user in a new line using loop. 
a = input("enter a string")
for i in a:
  print (i)
enter a stringDhanush
D
h
a
n
u
s
h
In [11]:
#program to find the length of the string "refrigerator" without using len function. 
a = "refrigerator"
count = 0
for i in a:
  count = count+1
print (count)
12
In [13]:
#program to Check if a Substring is Present in a Given String
string=input("Enter string:")
sub_str=input("Enter word:")
if(string.find(sub_str)==-1):
      print("Substring not found in string!")
else:
      print("Substring in string!")
Enter string:python programming is easy to learn
Enter word:easy
Substring in string!
