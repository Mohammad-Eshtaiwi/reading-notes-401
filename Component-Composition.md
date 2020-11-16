## React’s Props.Children

It is passing elemnts from the perent to the child as shown below

```
//App.js
render () {
  return (
    <div className='container'>
      <Picture key={picture.id} src={picture.src}>
          //what is placed here is passed as props.children
      </Picture>
    </div>
  )
}
```

## Review

Can a parent component access the state of a child component? No!

What can be passed along in a prop variable? State(variable) and behavior(methods)

How can a child component “know” the state of another component? using the context api or drilling the states from the perrent to the child which is bad

## Terms

- Props: components are like JavaScript functions. They accept arbitrary inputs (called “props”) and return React elements describing what should appear on the screen.

State: is similar to props, but it is private and fully controlled by the component.
