<div align="center">
  <h1>@system76/eslint-config-standard</h1>
  <h3>System76 standard eslint linting configuration</h3>
  <br>
  <br>
</div>

---

This is a System76 extension of [standard](https://github.com/feross/standard)
that includes many plugins for tools we use in our projects. It _does not_
change any standard rules. It does however add new ones.

## Using

```
npm install --save-dev @system76/eslint-config-standard
```

Then extend this in your own eslint configuration file:

```js
module.exports = {
  extends: [
    '@system76/standard'
  ]
}
```

## Deployment

Simply push to master and travis will do all the work for you!