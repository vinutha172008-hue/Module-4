# 1. Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
<img width="467" height="213" alt="Screenshot 2026-06-01 130619" src="https://github.com/user-attachments/assets/765fd3bd-ff22-4852-9449-7aa93f8a9c8d" />


## Output
<img width="440" height="148" alt="Screenshot 2026-06-01 130630" src="https://github.com/user-attachments/assets/be14a058-5353-4de2-a455-93eacd5e3495" />


## Result
The execution of the program was successfully done.


# 2. Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
<img width="422" height="220" alt="Screenshot 2026-06-01 130942" src="https://github.com/user-attachments/assets/7e88abcd-9e63-4974-bd34-41297e5b4de8" />


## Output
<img width="575" height="147" alt="Screenshot 2026-06-01 130950" src="https://github.com/user-attachments/assets/42225918-a4ae-49e5-9dad-f920d570eafe" />


## Result
The execution of the program was successfully done.

# 3. Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values


## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order


## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**


## 🧪Program
<img width="776" height="305" alt="Screenshot 2026-06-01 131419" src="https://github.com/user-attachments/assets/09fdafcd-76cd-4b1a-9a3b-45f401300866" />


## Sample Output
<img width="404" height="265" alt="Screenshot 2026-06-01 131426" src="https://github.com/user-attachments/assets/a8d48d9a-461f-4d04-8369-e6e977cb8062" />


## Result
The execution of the program was successfully done.

# 4. Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
<img width="437" height="176" alt="Screenshot 2026-06-01 131539" src="https://github.com/user-attachments/assets/806fa06c-8fda-4752-9966-5ac287f918f4" />


## Output
<img width="358" height="143" alt="Screenshot 2026-06-01 131546" src="https://github.com/user-attachments/assets/ee5d2c5b-ba55-4e42-9818-f10b53dbcb47" />


## Result
The execution of the program was successfully done.

# 5. File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
<img width="301" height="174" alt="Screenshot 2026-06-01 132526" src="https://github.com/user-attachments/assets/c8fc8e2e-5fe5-4836-9846-020ca7395290" />


## Output
<img width="383" height="186" alt="Screenshot 2026-06-01 132609" src="https://github.com/user-attachments/assets/c0789d06-1148-48ee-84cb-052009057276" />


## Result
The execution of the program was successfully done.
