# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (number){
  let numberArray = `${number}`.split("")
  let reversedNumberArray = numberArray.reverse()

  let newArray = []
  for (number of reversedNumberArray){
    newArray.push(+number)
  }

  return newArray
}
```

| Input | Output   |
| ----- | ------   |
|  54   | [4, 5]   | 
|  12   | [2, 1]   | 
|  324  | [4, 2, 3]| 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes an inputted number and returns an array with the digits of that number in reverse order.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
