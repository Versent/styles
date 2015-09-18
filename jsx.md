JSX
====

Naming
------

- Extension: Components that use JSX must be named `.jsx`
- Filename: Use PascalCase for filenames e.g. `MyComponent.jsx`

Handlers
--------

Use `onSomething` in present tense for handlers.

```
// good

<a onClick={this.onClick.bind(this)} >

// bad

<a onClick={this.handleClick.bind(this)}>

// bad

<a onClick={this.onClicked.bind(this)} >

```


Props
------


Always use camelCase for prop names.

```
// bad
<Foo
  UserName="hello"
  phone_number={12345678}
/>

// good
<Foo
  userName="hello"
  phoneNumber={12345678}
/>
```
