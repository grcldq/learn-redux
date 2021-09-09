# Redux

**Store** - Globalized State

**Action** - Simple function that returns an object
```js
const func = () => ({
  type: 'NAME_OF_ACTION',
  payload: {}
});
```

**Reducer** - pure function that takes an **action** and previous state of application and **returns the new state**
```js
const reducer = (state = 0, action) => {
  // some action here
  return state;
};
```