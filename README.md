# js-basics-arrays-and-objects

primitive values: number, boolean, null, and undefined.
Non-primitive values: Objects and arrays

** Differences 
  arr=[]  //Guess what console.log(arr[5]) will give!!
  var fruits = [ "apple", "orange", "mango" ];

  obj={key:value}

*** Arrays
** Arrays declaration
  examples to test:
  - var array1 = new Array(1, 2, 3);  // is there equal stament?
  - var array2 = new Array(3);
  - var array3 = new Array("3");

** Array Methods
 * isArray(valueToTest)
    Return False/True

 * concat()
    Returns a new array comprised of this array joined with other array(s) and/or value(s).

 * filter()
    Return new array depends on the condition

 * forEach()
    Calls a function for each element in the array.

 * includes()
    Determines whether an array includes a certain value among its entries, returning true or false 

 * indexOf()
    Returns the first index at which a given element can be found in the array, or -1 if it is not present.

 * reduce()
    Executes a reducer function (that you provide) on each element of the array, resulting in a single output value.
    check this out https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce

 * slice()
    Returns a shallow copy of a portion of an array into a new array object selected from begin to end (end not included) where begin and end represent the index of items in that array.
  
 * splice()
    Method changes the contents of an array by removing or replacing existing elements and/or adding new elements in place.
  
 * toString()
   Returns a string representing the specified array and its elements.


*** Objects
** Object declaration
   const objectName = {};

 * Object.assign()
   Copies the values of all enumerable own properties from one or more source objects to a target object.

 * Object.keys()
    Returns an array containing the names of all of the given object's own enumerable string properties.

 * Object.values()
    Returns an array containing the values that correspond to all of a given object's own enumerable string properties.

    **Qustions to think about togather**
    - How can we copy obj?
    - How can we reach specific element in Obj?




