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
