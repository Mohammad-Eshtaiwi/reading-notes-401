# Hooks

Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class. Hooks are backwards-compatible. This page provides an overview of Hooks for experienced React users.

# Revision

- Why do we not need more .html pages in a multi-page React app? separation of concerns
  If we wanted a component to show up on every page, where would we put it and why?

```
    Inside the <BrowserRouter />, outside a <Route />
```

So it passed as child prop

What does props.children contain? elements that passed from parent element

- Composition: To pass elements from parent to the child
- hash-based routing: using the portion of the page’s URL starting with #, i.e. the hash.
