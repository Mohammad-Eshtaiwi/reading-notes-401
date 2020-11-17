## React Router

React Router v4 is a pure React rewrite of the popular React package. Previous versions of React Router used configuration disguised as pseudo-components and could be difficult to understand. With v4, everything is “just components”.

## Review

Do child components have direct access to props/state from the parent? no

When a component “wraps” another component, how does the child component’s output get rendered? prop.children

Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application? yes

What trick can a parent use to share all props with it’s children? maybe the context api?

## Terms

props.children

```
<Main>
  <Content />
</Main>
```
