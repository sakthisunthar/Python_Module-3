## PYTHON PROGRAMMING MODULE 3
# Date: 24.3.26 

# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
items=[1,6,4,7,8,9,5,3]
sum_numbers=0
for x in items:
       sum_numbers+=x
print(sum_numbers)
```

## Output

![502980845-abd9193c-2533-4e3d-b10d-bf3f24183fcf](https://github.com/user-attachments/assets/9a4d954f-b14c-4e83-be52-ab889d954a0b)

## Result
The program successfully creates sum of all elements in list

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
i = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
a=r"^[^e]*$"
d=(n for n in i if re.match(a,n))
print(list(d))
```
## Output

![502987183-d7127b85-90be-432f-8c46-03807af54529](https://github.com/user-attachments/assets/3ebfd9e7-b308-4bd2-87ef-acf163020e7d)

## Result
The program successfully filters and returns all elements from the list that do not contain 'e',using regex


# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
items=[1,6,4,7,8,9,5,3]
sum_numbers=0
for x in items:
       sum_numbers+=x
print(sum_numbers)
```

## Output

![502981036-fcf58990-a2d1-4bf2-826e-4690b4e1165c](https://github.com/user-attachments/assets/5e46e669-9c81-4351-b354-ac2d77869207)

## Result
The program successfully takes a string and an index number from the user, removes the character at the specified index, and prints the modified string without that character.


# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
def palindrome(a):
    d=a[::-1]
    if a==d:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
a=input()
palindrome(a)
```

## Output

![502981261-8e96b317-1e16-4a8d-9418-40923750762f](https://github.com/user-attachments/assets/965c3b7b-0fd3-4656-a602-07152ad46eeb)

## Result
The program successfully checks whether the string 'google' is a palindrome or not


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
tuplex = ("S", 89, "R", "e", "s", "o", "u", "r", "c", "e","D")
print('r'in tuplex)
print('5'in tuplex)
```

## Output

![502981397-dfa9e34b-1e81-47e2-9cbd-042888edf4d0](https://github.com/user-attachments/assets/85d6c604-3a7d-405e-8adb-2b4102b8fb70)


## Result
The program successfully checks for the existence of both the character 'n' and the number 8 in the given tuple and prints True for each, confirming their presence.
