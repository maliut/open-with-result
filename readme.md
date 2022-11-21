for example:
```js
try {
  await open('http://xx', { app: { name: open.apps.edge } })
} catch (e) {
  console.error(e)
}
```
will throw:
```
Unable to find application named 'microsoft edge'
```

if edge does not exist
