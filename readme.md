forked from [sindresorhus/open](https://github.com/sindresorhus/open). Throw an error when open fails

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
