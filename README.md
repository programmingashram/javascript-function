**in simple language** - function is bunch of js code.in function we can able to fetch output when we call the function, in function we can create a seprate block of js code. in function we can create one time and we can use multiple times. where we need same code. we can call our function when another function is called.

### In JS We have multiple types of function ⚡

    1. Local Function
    2. Function with an arguments
    3. Arrow function
    4. Clouser Function
    5. Nested Function
    
#### 💡 Local Function
Local function is also known as simple function, we can write this simple function like that.

<code>
        function fnName(){
            console.log("Hello I am function...:)");
        }
        fnName();
</code>


#### 💡 Function with an arguements
in function with arguements we can pass the values dynmacly by arguements to parameters. and get the values from parameters and do what u want to do.

<code>
        function fnName(args1, args2){
            console.log(args1 + args2);
        }
        fnName(10, 10); - arguments
</code>


#### Arrow Function
Arrow function will allow us to create single line function. it's also called short hand function. it is the part of Javascript ES6.

<code>
      x = ()=> console.log("Hello I am arrow function");
      x();
</code>  


#### 💡 Nested Function.
In Nested function we can create a function in a function, it's also called child function. in this nested function child function will able to access parent function values.

    **For Example :-**

<code>
       function fn1(){
            console.log("Hello I am function First...:)");
            function fn2(){
                console.log("Hello Programer");
            }
            fn2();
        }
        fn1();
</code>  


#### 💡 Clouser Function.
Nested function and clouser function both are same, clouser allows us to access parent function properties and values. we can call our child function and will get the output. 

<code>
       function fn1(){
            let x = 10;
            function fn2(){
                console.log(x) // It will return 10;
            }
            fn2();
        }
        fn1();
</code>  
