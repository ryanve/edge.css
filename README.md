# edge.css

Functional CSS edges for use with `position`

## classes

- `.edge-0`
- `.edge-auto`
- `.top-0`
- `.left-0`
- `.right-0`
- `.bottom-0`
- `.top-auto`
- `.left-auto`
- `.right-auto`
- `.bottom-auto`

### composing

[Classes](#classes) are listed in order. `.edge-` classes affect all 4 edges. The others affect individual edges and are defined later such that `class="edge-0 top-auto"` will compose to `top: auto; left: 0; right: 0; bottom: 0;`

## setup

### install

```
npm install edge.css
```

### import

```
@import './node_modules/edge.css/edge';
```

## related

[position.css](https://github.com/ryanve/position.css)
