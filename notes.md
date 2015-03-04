# Notes on Learn Python the Hard Way

## DATA OUTPUT
#### print statement
We print objects such as strings and integers with `print`.
```python
print "Hello World!"
```

#### comments
Anything after `#` (a.k.a. octothorpe or pound key) is ignored by python.
```python
# A comment, this is so you can read your program later.
print "Hello World!"
```

#### strings
A string is a bit of text you want to display using `'` or `"`, and `'''` or `"""` for multi-line strings.
```python
print 'I am a string.'
print "I can also have double quotes around me."
print """
I am a string
that span across
multiple lines.
"""
```

#### numbers and math
Math operations in python follow the PEMDAS rule. These are the symbols used:
- `+` plus for addition
- `-` minus for substraction
- `/` slash for division
- `*` asterisk for multiplication
- `%` percent as modulus
- `<` less-than
- `>` greater-than
- `<=` less-than-equal
- `>=` greater-than-equal

```python
# This will give us the sum of 3 and 2
print 3 + 2
```

#### variables and names
A variable is a name for something, similar to how my name "Nadine" is a name for, "The girl who wrote these notes."
We use `=` to assign items into variables and `_` as space if need be.
```python
my_name = 'Nadine'
my_current_age = 23
```

#### variables and string formatting
Strings may contain the format characters such as `%s`, `%d`, and `%r` for printing the contents of our variable.
- `%d` - for printing numeric values
- `%r` - for printing out the actual contents of the variable for debugging purposes

```python
my_name = 'Nadine
my_current_age = 23
height = '5\'7"'
print "Hi, my name is %s and I am %d years old. I stand %r tall." % (my_name, my_current_age, height)
```
will give us...
```
> Hi, my name is Nadine and I am 23 years old. I stand '5\'7"' tall.
```

#### escape sequences
There are various "escape sequences" available for different characters you might want use for different purposes.
```python
"I am 6'2\" tall."  # escape double-quote inside string
'I am 6\'2" tall.'  # escape single-quote inside string
```
Commonly used ones:
- `\\` - show backslash
- `\'` - show single-quote
- `\"` - show double-quote
- `\n` - line break
- `\r` - return carriage
- `\t` - tab

## DATA INPUT

#### using raw_input()
`raw_input()` lets the user enter data WHILE the script is running, like this.
This prompts the user with "What is your name?" and puts the result into the variable `your_name`. This is how you ask someone a question and get the answer.
```python
your_name = raw_input("What is your name?")
print "Hi %s. It's nice to meet you." % your_name
```

#### using argv
`argv` lets the user enter data BEFORE the script is run, like this:
```
$ python my_script.py Nadine Nads
```
`argv` holds the arguments (i.e. "Nadine" and "Nads") we passed to our Python script when we ran it.
```python
from sys import argv # We use the sys module for this feature

# This "unpacks" argv so that, rather than holding all the arguments, it gets assigned to variables we can work with.
script, your_name, your_nickname = argv

print "The script is called:", script
print "My name is %s, but you can call me %s." % (name, nickname)
```
