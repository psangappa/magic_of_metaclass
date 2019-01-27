You might have heard this thousands of time that everything in python is an object.
For example,
```
>>> type(4)
<class 'int'>
>>> type('y')
<class 'str'>
```

As seen above, even basic types like integers and strings are objects.Since everything is an object and object is an instance of a class, thwn what is a class?

Let's see this in details,

```
>>> type(int)
<class 'type'>
>>> type(str)
<class 'type'>
```

Ironically, class are object too. They're insyance of the 'type' class or they're the instance of the type 'metaclass'.

Now, lets see what is metaclass. 

## Metaclass create Classes and Classes creates objects

[![Meta-logo](https://github.com/psangappa/magic_of_metaclass/blob/master/download.png?raw=true)](/)




