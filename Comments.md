#Comment
Comment is used to make code readable. A programming language has limitation that we can�t be declared as we talk in general English. Moreover comments are defined so that a non-programmer can understand the things a program is doing.

example:
```
def xyz():
  print "hello"

xyz()
```

Above code would not be understandable to a non-programmer.

But Check out below
```

def xyz():#function with name xyz defined which would be used to print hello on screen
  print "hello"
  """
  The above print function is used to print anything that is provided to it using std:in
  """

xyz()
#xyz() is used to call the function which would call the defined function xyz() would print hello
```

The second block is more readable than first one. This type of comments are also used so that when in future if we refer our code we can check what and why we had written particular code block

----
####Comments 
Comments are of two types:
1)Single Line Comment
2)Multi Line Comment


#####Single Line Comment
Single Line Comment can be declared by using <code>#</code> i.e. hash


```
#this is comment
```

#####MultiLine Comment
Multi Line Comment can be declare by 
<code>""" (text) """ </code>


```
"""
This is first comment.
This is second comment.
.
.

"""
```
