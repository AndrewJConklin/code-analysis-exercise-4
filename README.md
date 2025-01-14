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
  for (number in reversedNumberArray){
    newArray.push(+number)
  }

  return newArray
}
```

| Input | Output |
| 1     | [0]    |
| 12    | [1, 2] | 
| 123   |[1, 2, 3]| 
| 1234  |[1, 2, 3, 4]| 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes an inputted number, turns it into a string, splits the string into an array, reverses the array, then takes the index of each number and returns a new array with the indexes of the numbers.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
