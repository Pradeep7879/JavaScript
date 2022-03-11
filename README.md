# JavaScript
Interview and more about JavaScript
--------------------------------------------------------------------------------------

        Function Sequence
        JavaScript functions are executed in the sequence they are called. Not in the sequence they are defined.



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
        
        -------------------------------------
        A JavaScript Promise object can be:

            1. Pending
            2. Fulfilled
            3. Rejected
            The Promise object supports two properties: state and result.

            While a Promise object is "pending" (working), the result is undefined.

            When a Promise object is "fulfilled", the result is a value.

            When a Promise object is "rejected", the result is an error object.
            
        You cannot access the Promise properties state and result.

        You must use a Promise method to handle promises.
        
 What is callback..?
 
        A callback is a function passed as an argument to another function
        basically it allows a function to call another function
        And callback function can run after another function has finished
        
        callback are in asynchronous functions, where one function has to wait for another function (like waiting for a file to load).
        
 What is Asynchronous.?
 
        Functions running in parallel with other functions are called asynchronous
        A good example is JavaScript setTimeout() and setInterval()
        
 What is 'this' keyword..?
 
        this functions the this keyword represented the object that called the function
        arrow functions there are no binding of this
        
 What is Prototype..?
 
        JavaScript prototype property allows you to add new properties to object constructors, also allows you to add new methods to objects constructors:
        The Object.prototype is on the top of the prototype inheritance chain:

        Date objects, Array objects, and Person objects inherit from Object.prototype. 
        
 What is the difference between var, let and const..?
 
        	Re-declare	update	remark					                                        scope
        var 	yes	        yes	scope within function |	variable can be access from outside the function	function, global
        let	no	        yes	block scope	      |				                                block, function, global
        const	no	        no	access within block   |					                        block, function, global
                {}block scope can not access outside of the block							

        
 
       

        
    
 
