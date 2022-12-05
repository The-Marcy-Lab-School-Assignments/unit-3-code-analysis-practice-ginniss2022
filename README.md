# unit-3-code-analysis-practice

Using markdown, identify what the following code block does and explain how the `forEach` function works.

```js
function forEach(arr, action) {
  for (let i = 0; i < arr.length; i++) {
    action(arr[i]);
  }
}

forEach(['a', 'b', 'c'], console.log);
```

**Guiding Questions:**
* What does the code do (what does it print? are any variable reassigned? etc...)
* What are the expected data types for each of the parameters?
* When the function is invoked, what value are provided as arguments?
* How does `forEach` use the provided arguments?

**Key Terms to use**: parameters, arguments, invoke/invocation, iterate, "element of the array", increment,  

<hr>

Your explanation here...
- The function `forEach` prints 

Solution:

```
a
b
c
```
- The `arr` parameter expects an array to be passed through as an argument.
- The `action` parameter expects a function to be passed through as an argument.
- `forEach` iterates through each element of the array and invokes the function `console.log()` as the index is incremented.
