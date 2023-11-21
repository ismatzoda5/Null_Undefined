 # <span style="color:skyblue">  Java Script: Differences between Null and Undefined.</span>


## <span style="color:"> Introduction

![Null](./0-null-undefined.png)

### - In JavaScript, null and undefined are two  values used to represent empty or non-existent values. 

## <span style="color:skyblue">Null</span>
* In JavaScript, null is a primitive. It is used to indicate that a variable or object property has no value.

![Null](./1_SYsFgvpVRVrCl_d393PNFA.png)
For example:
javascript
* let myVariable = null;
* console.log(myVariable);  
* // Output: null


## <span style="color:skyblue"> Undefined
* Undefined in JavaScript represents variables or object properties that have been declared but have not been assigned a value.

![Undefined](./1_hpuHy9g79vBNJPYNOr48fw.webp)

Consider the following example:
javascript
let myVariable;
console.log(myVariable);  // Output: undefined


## <span style="color:skyblue"> Comparison with false
In JavaScript,<span style="color:red"> false </span>is a <span style="color:greenyellow">Boolean</span> value representing "false". Let's compare null and undefined with false using the equality operators.

### <span style="color:red"> false == Null
When using the double equals (==) operator, which performs type coercion, false == null evaluates to false.

javascript
console.log(false == null);  // Output: false


### <span style="color:red"> Undefined == false
Similarly, when comparing undefined with false using the double equals (==) operator, it also evaluates to false.

javascript
console.log(undefined == false);  // Output: false


## <span style="color: greenyellow"> Conclusion 

let myVariable = null;
console.log(myVariable);  // Output: null

let myVariable;
console.log(myVariable);  // Output: undefined

console.log(false == null);  // Output: false
console.log(undefined == false);  // Output: false