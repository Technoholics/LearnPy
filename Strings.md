#Strings
We have already seen how to declare a variable. How to assign string to it and print it.
```
soup = "tomato soup"
print soup

```

String could be declared using both apostrophe(') or double quote(").

Suppose when you have statement like this "I don't have your book." then this could be declared as follows
```
statement = "I don't have your book."
```

When you are working with apostrophe

```
statement = 'I don't have your book.'
```

Above code would show a syntax error. This is caused because of ’t i.e. apostrophe t. This is because interpreter thinks that there is end of string at n, but which is not a case. So during such situation we can use escape sequence.
The statement can be declared as below:
```
statement = 'I don\'t have your book.'
#here \ is a escape sequence
```
##Array
When we declared a string suppose for example name = "Bhavesh", then the actual assignment is done as array. A memory space of the number of character in string is created starting with zero. And all character are stored in it character wise. The variable name would be having array as below
```
name[0]='B'
name[1]='h'
name[2]='a'
name[3]='v'
name[4]='e'
name[5]='s'
name[6]='h'
```
Here in above 0,1,2...6 are called index of an array. At each index only one single variable is present. At index 0 'B', at index 1 'h' and so on
 Working with Array is so awesome. Consider the following code:
 ```
 third_letter = "Bhavesh'[2]
 ```
 The above code would assign a to third_letter.
 ---
##String Manipulation

There are some predefined methods used for manipulating strings or else working with strings. Out of which we are going to see few

1. len()
2. lower()
3. upper()

### len()
len() is used to calculate length of a string. For example suppose you want to find length of "LearnPy", then you can do that by `len("LearnPy")` you would get output as 7. Or else if you have a variable then its length can be calculated as `len(hello)`. That is you can provide string or variable both.
### lower()
lower() is used to convert sting into lower case. for example 
```
hello="LearnPy"
hello.lower()
```
The output of above code would be `learnpy`
### upper()
upper() is used to convert sting into upper case. For example 
```
hello="LearnPy"
hello.upper()
```
The output of above code would be `LEARNPY`
