# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (let dog of person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
|(Mark, Patch) const mark = {name: "Mark", dogs:[{name:"Patch"' breed: "Lab", age: "10"]} | {name:"Patch"' breed: "Lab", age: "10" }|
|(Sara, Lexie) const sara = {name: "Sara",dogs:[{name:"Lexie", breed: "shnauzer", age="3"}]}| {name:"Lexie", breed: "shnauzer", age="3"}| 
|(Mel, Wishbone) const mel = {name: "Mel", dogs:[{name:"Paxie" breed: "German Sheperd", age="1" }]}| error, Wishbone not found| 

<table>
  <tr>
    <th>What does this program do?</th>
    <td> It loops through an array associated to the person to see if the petname argument is found. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
