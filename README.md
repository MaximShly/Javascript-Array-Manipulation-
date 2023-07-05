# Javascript-Array-Manipulation-
Continued manipulation basics - using Slice/Splice/Split commands built into Java


In the sliceElements function, we use the slice() method to return the last three elements of givenArray. slice(-3) starts slicing from the third last element to the end of the array.

In the spliceElements function, we use the splice() method to remove the last element of givenArray and add element1 and element2 in its place. splice(givenArray.length - 1, 1, element1, element2) starts at the last index of the array (which is givenArray.length - 1), removes one element, and then adds element1 and element2.
In the splice method, the first argument is the index at which to start changing the array, the second argument is the number of elements to remove, and the following arguments are the elements to add.
So in the expression givenArray.splice(givenArray.length - 1, 1, element1, element2), the 1 is the number of elements to remove from the array, starting from the index givenArray.length - 1.
In other words, this method call is saying "start at the last element of the array (givenArray.length - 1), remove one element (1), and then add element1 and element2 in that place".

In the splitElements function, we use the split() method to convert givenString into an array of words. split(' ') splits the string into an array at each space character.
