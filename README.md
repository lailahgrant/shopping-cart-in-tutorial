# JavaScript Shopping Cart Tutorial

## 1. Array Basics Intro
> Shopping cart is basically a list.
> You buy something from the store, add something from the store to the cart and when you view items in the list - you'll see them.
>
> <hr>
> Array is an ordered list organized by index.
> The list will be an array:
> var array = [ ]; //list of multiple items
> You can add or remove items from an array
>
> <hr>
> Example
> var array = ["A", "b", "c", "d"];
> console.log(array);
>
> <hr>
> To view individual items in an array:-
> - Each item in an array is stored at an <strong>index</strong>.
> 
> - Index starts at <b>0</b>.
> - There's no index before 0, first item will be at 0 index.
> Example
> console.log(array[0]); // this will give the first item in an array
>
> <hr>
> console.log(array.length); //number of items in an array
>
> <hr>
>
>  Add an item to an array: 
> - <b>push()</b> - adds an item into the array
>
> <hr>
>
> - Loop through an array 
> a) For loop
> <pre>
> for(var i=0; i < array.length; i++){
>     console.log(array[i]); //gives the items in the array
>}
> </pre>
>
> <hr>

## Object Basics Intro


> - Object - is a collection of methods and properties.
> - Object is a collection organized on a key.
> - Key is a named position. <b>key-value</b>
> <hr>
> Example
> <pre>
> var obj = { key:10, a:33; b:"Name" };
> </pre>
> 
> - key can be anything that starts with a letter
> - value can be anything or any datatype
> - objects can have a string-key e.g. 
> var obj = {"key": 23};
> <hr>
> Example 2
> <pre>
> var obj = {name:"Apple", cost:1.99, count:2};
> console.log(obj);
> </pre>
>
> How to access individual items in an object
> <pre>
> console.log(obj.name); //use the key
> </pre>
><hr>
> 
> - Use <b>for..in </b> loop to iterate an object
> <pre>
>   for(var key in obj){
>       console.log(key+" "obj[key]);
> }
> </pre>
>
> <b>for..in </b>loop can be used on arrays too:-  
> <pre>
> var a = ["A", "B", "C"];
> for(var j in a){
>    console.log(j+" "+a[j]);
>        }
> </pre>
> <hr>

## 3. Arrays and Objects




## 4. Functions
> Function is a block of code that can be reused.
> // Function names should be descriptive
> - Function can be used to generate an object.
> - Function has to be invoked or called in order to execute it
> <pre>
> function myfunction(){
>   console.log("hello Lailah");
> }
> myfunction();
> </pre>
>
> <hr>
> 
> - Functions can take parameters - one and more.
> <pre>
> function myfunction(message){
>   console.log(message);
> }
> myfunction("Hello Lailah");
> </pre>
>
> <pre>
> function myfunction(message, count){
>  for(var i=0; i < count; i++ ){
> console.log(message);
> }
> }
> </pre>
>
> <hr>
>
> <pre>
> function square(num){
>    return num*num; 
>    //console.log(square())//nothing is run after the return statement
>        }
>        console.log(square(4));
> </pre>
>
> <hr>


## 5. Scope
> Scope determines where a variable or value is visible.
>
> Scope applies to everything e.g. functions,arrays, objects etc
>
> Example
> //passing a variable to 2 or more different scripts
> <pre>
>  <script>
>    var global = "Hello";
>    </script>
>    <script>
>    console.log("Global "+global);
>    </script> 
> </pre>
> 

## Cart Item and Cart

> <pre>
> //An  object in an array
>        //name  price  count or quantity of items in the cart
>        var cart = [  ];
>
>        //Item will make item objects for us
>        //Item is a function literal
>       //Item is  a class (capital I) - naming convention
>        var Item = function(name, price, count){
>            //this represents that object(Item), this.name - .name is the property name, =name is the parameter passed in the function(name)
>            this.name = name 
>            this.price = price
>            this.count = count
>        };
>
>        //create an object in js
>        //a is the Instance of class (small b)
>        var brush = new Item("Brush", 1.99, 1); //<- this is the same as -> {name:"Brush", price: 1.99, count:1};
>        console.log(brush); //Item {name: 'Brush', price: 1.99, count: 1}
>
>        //create a new object
>        cart.push(new Item("Apple", 2.12, 1));
>        cart.push(brush);
>
>        console.log(cart);
> 
> </pre>
>

## 7. Shopping Cart Functions
>  Function names should be descriptive 


## 8. addItemToCart()


## 9. removeItemFromCart() 
> removeItemFromCart(name) //Removes one Item
>
> Can be used for <b>decrement</b> or <b>-</b> button on a cart.


## 10. removeItemFromCartAll() 
> //removeItemFromCartAll(name) //removes all item name
> can be used to delete items in a cart.
>

## 11. a) clearCart()
> can be used to Empty cart
>

## 11. b) countCart()   
> returns total count
> it returns the value - total number of items in the cart
>

## 11. c) totalCart()   
> returns total cost
>


