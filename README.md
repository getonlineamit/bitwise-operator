# Bitwise Operator

> The operands of all bitwise operators are converted to signed 32-bit integers in two's complement format.Every number has it's own binary representation, used by those operators. To check dec number's binary value, we use `.toString()` method with base argument - '2' for binary.

**Sometime we even use Bitwise OR as equivalent of Math.floor()**
  ```
  Example - 
  var temp = 2.987293874;
  var result = temp | 0;
  ```
  
**Few Uses of bitwise operator** 

- We can convert colors from RGA to Hex format.
- Variables swap without using third variable (hint - using xor)(redundant with ES6 swap [a, b] = [b, a]).
- Check if number is even or odd  `Even Number => [(n & 1) === 0]`

**More resources**
- https://miguelmota.com/blog/bitwise-operators-in-javascript/
- https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators
- https://chrisrng.svbtle.com/bitwise-operators-in-javascript
- https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators
