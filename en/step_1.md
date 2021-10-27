## Using the `list()` function in Python

The `list()` function **returns** a list that you can use in your code. 

If you use `list()` with no **parameters** in the curved brackets, it will **return** an empty list. 

Here is an example of `list()` being used with **no parameters**. 

```python
print(list())
```

The output of this code would be:

```
[]
```

This is because the `list()` function has **returned** an empty list. 

### Converting a string into a list

You can use the `list()` function to convert a string into a list. 

For example, you might have a **variable** that holds the vowels from the English alphabet. To convert this into a list you would **pass** the `vowels` variable through the **parameters** (round brackets) and the function would return it as a list. 

You can see this happening at **line 2** in the code example below:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 2
---
vowels = 'AEIOU' # The variable holds a string of vowels
vowel_list = list(vowels) # Create a list that holds each vowel as a separate item
print(vowel_list) # Display the list of vowels
--- /code ---

The output of this code would be:

```
['A', 'E', 'I', 'O', 'U']
```





