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

- What are cors and what it is responsible about
- malware functions and how to create it and use it
- how to write better code and start writing from the first without the need to refactor it

### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

- how to use sessions and cookies
- how to implement authentication and authorization
- how to write automation tests

### What are you most excited about trying to implement or see how it works?

how to create full-stack applications using node and react with advance features

# NodeJs

NodeJs is a JavaScript runtime built on Chrome’s V8 JavaScript engine. which mean your javascribt will work outside the browser. and to do that nodeJs use v8 JavaScript engine. but nodeJs use enhanced v8 engine to make it work outside of the browser.

**_to compile a js file simply write node filename.js in the console then boom it works_**

# npm

npm used to download packages into your project.

```
npm init -y
```

This will create and auto-populate a package.json file in the same folder.

Node.js is single-threaded. It’s also event-driven, which means that everything that happens in Node is in reaction to an event. For example, when a new request comes in (one kind of event) the server will start processing it. If it then encounters a blocking I/O operation, instead of waiting for this to complete, it will register a callback before continuing to process the next event. When the I/O operation has finished (another kind of event), the server will execute the callback and continue working on the original request. Under the hood, Node uses the libuv library to implement this asynchronous (that is, non-blocking) behavior.

Node’s execution model causes the server very little overhead, and consequently it’s capable of handling a large number of simultaneous connections. The traditional approach to scaling a Node app is to clone it and have the cloned instances share the workload. Node.js even has a built-in module to help you implement a cloning strategy on a single server.

JavaScript is everywhere, and Node is a vast and expansive subject. Nonetheless, I hope that in this article I’ve offered you the beginner-friendly, high-level look at Node.js and its main paradigms that I promised at the beginning. I also hope that when you re-read the definitions we looked at previously, things will make a lot more sense.
