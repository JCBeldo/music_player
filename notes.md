the ... spread syntax allows for iterables to be placed in an arg or another value store like arrays or obj.  ex: sum(...arr) where arr is an array of numbers.  kinda like 0..10 in Ruby. fills in the values into the arg.  

arrow notation for functions 
ex: const name = (param) => {
  return param;
};

The map() method is used to iterate through an array and return a new array. It's helpful when you want to create a new array based on the values of an existing array. For example:

const numbers = [1, 2, 3];
const doubledNumbers = numbers.map((number) => number * 2); // doubledNumbers will be [2, 4, 6]
Notice that the map() method takes a function as an argument. This is called a callback function, which is a function that is passed to another function as an argument. In the example above, the callback function is (number) => number * 2, and it's run on each element in the numbers array. The map() method then returns a new array with the results.