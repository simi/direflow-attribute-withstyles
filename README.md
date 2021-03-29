# Reproducer of withStyles bug

```
$ yarn install
$ yarn run start
```

## Expected

Since in `public/index.html` is component with attribute `componentTitle="My new title"` present, I would expect the value of componentTitle to be "My new title" on initial component render.

## Actual

Default value of `componentTitle` attribute is used for initial render)
