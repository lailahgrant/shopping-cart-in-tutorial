# JavaScript Shopping Cart Tutorial

## Array Basics
> Shopping cart is basically a list.
> You buy something from the store, add something from the store to the cart and when you view items in the list - you'll see them.
>
> <hr>
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