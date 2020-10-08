# Review

## Array.map()

return a new array with the same size as the original with a manipulation based on the provided function.

```
var numbers = [4, 9, 16, 25];
var x = numbers.map(Math.sqrt)
```

## Array.reduce()

reduce the array into a single value

```
var numbers = [175, 50, 25];

document.getElementById("demo").innerHTML = numbers.reduce(myFunc);

function myFunc(total, num) {
  return total - num;
}
```

## superagent()

npm package used to call apis

### using await

```
async function cityData(city){
  const {body} = await superagent(`https://geocode.xyz/${city}?json=1`)
  console.log(body);
}
cityData("amman")
```

### using promises

```
function getCharacters(){
 superagent("https://swapi.dev/api/people/").then(({body})=>{
   const characters = body.results.map(item=> item.name)

   console.log(characters)
 })
}
```

#### Which 3 things had you heard about previously and now have better clarity on?

-   What are cors and what it is responsible about
-   malware functions and how to create it and use it
-   how to write better code and start writing from the first without the need to refactor it

### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

-   how to use sessions and cookies
-   how to implement authentication and authorization
-   how to write automation tests

### What are you most excited about trying to implement or see how it works?

how to create full-stack applications using node and react with advance features
