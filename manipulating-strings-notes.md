# Manipulating Python Strings / Notes

- By the end of this lesson, you should be able to:
    - use the `len()` function to count the number of characters in a string
    - use **square bracket notation** to extract (get or grab) a single character from a string
    - use **square bracket notation** and **index numbers** to slice several characters out of string
    - convert a string to uppercase characters
    - convert a string to lowercase characters
    - use single and double quotes correctly with a string
 
## Things To Remember About Working with Strings

- You can manipulate or work with strings in several different ways to produce useful information
- A **string** is an example of a **data type** you can work with in Python
- Other Python data types include:
    -  numeric (numbers)
    -  lists (known as **arrays** in other programming languages)
    -  dictionaries
    -  Boolean data type (Booleans represent one of two values: `True` or `False`)
- **String data** is always treated as text in your Python script, even if it contains numeric characters
    -  `first_name = 'Alyssa'` (where **Alyssa** is a string)
    -  `street_address = '457 Oak Street'` (where **457 Oak Street** is also a string, even though it contains the number 457)
- You mark the beginning and end of a string in Python with a pair of single or double quotation marks  (see the `first_name` and `street_address` variables above)
- You can't do math directly with strings -- you have to convert a string to the numeric data type first
- You can compare strings to see if they are equal, i.e., to see if they match
    -  Example: Entering a password twice to make sure they match
- Python offers lots of built-in string functions you can use to work with strings
    - Example: The `len()` function returns the number of characters in a string
    - Built-in functions are already part of the Python language, so you just use them when needed (you don't have to create a built-in function because it already exists)
    - NOTE: A blank space also counts as a character in a string
 
## Helpful Resource
- [How to Index Strings in Python](https://codingwithestefania.hashnode.dev/python-string-indexing-how-to-get-characters#heading-using-the-character)
 
## Code Examples

### Example 1: The len( ) Function

```
# Returns 6 because there are six characters in the word banana
len('banana')
```

### Example 2: Storing the returned value in a variable
```
character_count = len('banana')
# Prints the number of characters found in the word banana
print(character_count)
```

### Example 3: Prompting user to enter a word and getting the length of the string
```
print('Please enter a word (Example: cat):')
word = input ( )

# Returns the length of the string and assigns the string length to the variable word_length
word_length = len(word)
# Prints the number of characters found in the word the user entered
print(word_length)

```
### Example 4: A more efficient way to write the code shown in Example 3
```
# Get input from the user and store user's input in the variable word
word = input('Please enter a word (Example: cat):')
# Use the `len()` function within the `print()` function
# This is known as nesting functions (writing one function inside another)
print(len(word))
```
