#Strings
We have already seen how to declare a variable. How to assign string to it and print it.
```
soup = "tomato soup"
print soup

```

String could be declared using both apostrophe(') or double qoute (").

Suppose when you have statement like this "I don't have your book." then this could be declared as follows
```
statement = "I don't have your book."
```

When you are working with apostrophe

```
statement = 'I don't have your book.'
```

Above code would show a syntax error. This is caused because of 't i.e. apostrophe t. This is because intepretor thinks that there is end of string at n, but which is not a case. So during such situation we can use excape sequence.
The statement can be declared as below:
```
statement = 'I don\'t have your book.'
#here \ is a excape sequence
```
##Array
When we declared a string suppose for example name = "Bhavesh", then the actuall assignment is done as array. A memory space of the number of character in string is created starting with zero. And all character are stored in it character wise. The variable name would be having array as below
name[0]='B'
name[1]='h'
name[2]='a'
name[3]='v'
name[4]='e'
name[5]='s'
name[6]='h'
Here in above 0,1,2...6 are called index of an array. At each index only one single variable is present. At index 0 'B', at index 1 'h' and so on
