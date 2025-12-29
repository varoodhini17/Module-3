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
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner']
filt=[]
for item in items:
    if 'e' not in item:
        filt.append(item)
print(filt)
```
Add code here
## Output

<img width="433" height="176" alt="image" src="https://github.com/user-attachments/assets/40160040-2edc-47bc-aeb4-33972ed7e5af" />

## Result
Thus, the program has been successfully executed.
