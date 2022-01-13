# JavaScript
Interview and more about JavaScript
--------------------------------------------------------------------------------------

What is Destructuring and Spread in JavaScript..?
    
    Object destructuring and Spread syntax are not the same thing.

    Spread syntax (also known as the Spread Operator) is used to copy the enumerable properties of an object to create a clone of it.
    We can also update an object or merge with another object using the spread syntax.

    The Rest parameter is kind of the opposite of the Spread syntax. It helps to consolidate (or collect) the remaining object properties
    into a new object while destructuring is done.
    
    https://www.freecodecamp.org/news/javascript-object-destructuring-spread-operator-rest-parameter/
    
What is the Closures..?
    
       Closures are important because they control what is and isn’t in scope in a particular function, 
       along with which variables are shared between sibling functions in the same containing scope. 
       **A closure is a function having access to the parent scope, even after the parent function has closed.**

What is Promises..?

        How Promises Work
        A promise is an object which can be returned synchronously from an asynchronous function. It will be in one of 3 possible states:
        
        Fulfilled: onFulfilled() will be called (e.g., resolve() was called)
        Rejected: onRejected() will be called (e.g., reject() was called)
        Pending: not yet fulfilled or rejected
        
        A promise is settled if it’s not pending (it has been resolved or rejected). 
        Sometimes people use resolved and settled to mean the same thing: not pending.
        
        Once settled, a promise can not be resettled. Calling resolve() or reject() again will have no effect. 
        The immutability of a settled promise is an important feature.
        
        
    
 
