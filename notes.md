- the ... spread syntax allows for iterables to be placed in an arg or another value store like arrays or obj.  ex: sum(...arr) where arr is an array of numbers.  kinda like 0..10 in Ruby. fills in the values into the arg.  

- arrow notation for functions 
  ex: const name = (param) => {
    return param;
  };

- The map() method is used to iterate through an array and return a new array. It's helpful when you want to create a new array based on the values of an existing array. For example:

- const numbers = [1, 2, 3];
  const doubledNumbers = numbers.map((number) => number * 2); // doubledNumbers will be [2, 4, 6]
  Notice that the map() method takes a function as an argument. This is called a callback function, which is a function that is passed to another function as an argument. In the example above, the callback function is (number) => number * 2, and it's run on each element in the numbers array. The map() method then returns a new array with the results.

- The sort() method accepts a compare callback function that defines the sort order.

  In this example, the first condition (a.name < b.name) checks if the name of the first fruit is less than the name of the second fruit. If so, the first fruit is sorted before the second fruit.

  Strings are compared lexicographically which means they are compared character by character. For example, "Apples" is less than "Bananas" because "A" comes before "B" in the alphabet.

  The reason why this example is returning numbers is because the sort() method is expecting a number to be returned. If you return a negative number, the first item is sorted before the second item.

- The find() method retrieves the first element within an array that fulfills the conditions specified in the provided callback function. If no element satisfies the condition, the method returns undefined.