# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
Reg.No: 212223060239
Name: SANDHIYA G

import re
def find_match(s):
    print("Found a match!" if re.fullmatch(r'[a-z]+@[a-z]+', s) else "Not matched!")
    
user_input=input()
find_match(user_input)
```
### OUTPUT
<img width="591" height="174" alt="image" src="https://github.com/user-attachments/assets/5cae92ca-5484-4127-b93d-e8edd34dc837" />

### RESULT
Thus a Python program using regular expressions was executed and implemented successfully.

