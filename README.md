# module-3
# Exp. No: 3a  
## String– check whether an entered string is a palindrome or not without using built-in functions Available in Python
###  Aim
To write a Python program to check whether the entered string is a palindrome or not without using built-in functions.

---

###  Algorithm

Start

Input a string from the user.

Initialize a variable rev as an empty string.

Using a for loop, traverse the string from the last character to the first character and append each character to rev.

Compare the original string with the reversed string:

If both are equal → The string is a palindrome.

Otherwise → The string is not a palindrome.

Display the result.

Stop

---

### 🧾 Program
```
def isPalindrome(s):
    return s==s[::-1]
s=input()
ans=isPalindrome(s)
if ans:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```
### OUTPUT

<img width="918" height="207" alt="image" src="https://github.com/user-attachments/assets/f177a22a-a698-45c8-8670-ac57085a9bc6" />

### RESULT

Thus, the program to check whether the entered string is a palindrome or not without using built-in functions was successfully executed and verified.





# Exp. No: 3b  
## Regex – find sequences of lowercase letters joined with a underscore

###  Aim
To write a Python program to find all sequences of lowercase letters joined with an underscore using regular expressions.

---

###  Algorithm

Start

Import the re module.

Input a string from the user.

Define a regular expression pattern:

Pattern → r'[a-z]+_[a-z]+'

Explanation:

[a-z]+ → one or more lowercase letters

_ → underscore

[a-z]+ → one or more lowercase letters after underscore

Use re.findall(pattern, string) to find all matching sequences.

If matches are found → display them.

Otherwise → display “No matches found.”

Stop

---

### 🧾 Program
```
import re
def tiger(t):
    y='[a-z]+_[a-z]+$'
    if re.search(y,t):
        return('Found a match!')
    else:
        return('Not matched!')
str = input()
print(tiger(str))
```
### OUTPUT

<img width="611" height="189" alt="image" src="https://github.com/user-attachments/assets/d81891de-ebef-4f3f-b5d4-b4654b2414df" />


### RESULT

Thus, the Python program successfully finds all sequences of lowercase letters joined with an underscore using regular expressions.






# Exp. No:  3c
## List – sum all the items in a list

###  Aim
To write a Python program to sum all the items in a list.
---

###  Algorithm

Start

Input the number of elements in the list.

Create an empty list to store the elements.

Using a loop, read each element from the user and append it to the list.

Initialize a variable total = 0.

Traverse the list using a for loop and add each element to total.

Display the final sum.

Stop
---

### 🧾 Program
```
items=[11,12,13,15]
sum=0
for i in items:
        sum += i
print(sum)
```

### OUTPUT

<img width="316" height="162" alt="image" src="https://github.com/user-attachments/assets/c3c2919d-c1a2-4af7-8df5-618e64b8ba70" />


### RESULT

Thus, the program to sum all the items in a list was successfully executed and verified.







# Exp. No: 3d  
## Tuples – create the tuple using the numbers entered by the user, get the size of the tuple from the user.

###  Aim
To write a Python program to create a tuple using numbers entered by the user and get the size of the tuple from the user.

---

###  Algorithm

Start

Input the size of the tuple (n) from the user.

Create an empty list to temporarily store the numbers.

Using a for loop, read n numbers from the user and append them to the list.

Convert the list into a tuple using tuple().

Display the created tuple.

Display the size of the tuple using len().

Stop

---

### 🧾 Program

```
size=int(input())
elements=[]
for i in range(size):
    element=input()
    elements.append(element)
tuple_data=tuple(elements)
print(tuple_data)
```

### OUTPUT

<img width="856" height="332" alt="image" src="https://github.com/user-attachments/assets/79ee9a27-f6c3-402b-adf9-1269f1f601a8" />

### RESULT

Thus, the program to create a tuple using numbers entered by the user and get its size was successfully executed and verified.

# Exp. No: 3e 
## SEB – Write a python function that accepts a string and removes all the consonants from the string.

###  Aim
To write a Python function that accepts a string and removes all the consonants from the string.

---

###  Algorithm

Start

Define a function remove_consonants(string).

Create an empty string result to store only vowels.

Define a string containing all vowels → "aeiouAEIOU".

Traverse each character in the input string:

If the character is a vowel or not an alphabet, add it to result.

Otherwise, skip it (consonants are removed).

Return the result string.

Get input from the user and call the function.

Display the final string.

Stop

---

### 🧾 Program
```
def remove(s):
    vowel='aeiouAEIOU'
    t=tuple(s)
    for i in t:
        if i in vowel:
            print(i,end="")
    
        
```


### OUTPUT

<img width="510" height="161" alt="image" src="https://github.com/user-attachments/assets/82059e24-9364-4e8f-b019-3ac6a5da5c2b" />

### RESULT

Thus, the Python function to remove all the consonants from a string was successfully executed and verified.






```

```
