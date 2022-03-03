# Generators
Python provides a generator to create your own iterator function. A generator is a special type of function which does not return a single value, instead, it returns an iterator object with a sequence of values. In a generator function, a yield statement is used rather than a return statement. The following is a simple generator function.

![Generator2](https://user-images.githubusercontent.com/86805669/156532119-4de65b38-8e29-4b51-95fb-eba18b8f6125.PNG)


The generator function cannot include the return keyword. If you include it, then it will terminate the function. The difference between 'yield' and 'return' is that yield returns a value and pauses the execution while maintaining the internal states, whereas the return statement returns a value and terminates the execution of the function.


![image](https://user-images.githubusercontent.com/86805669/156531173-e232be66-a701-41c7-b783-a56d6c906d82.png)
