# map-pick-sass
Picking key, value from map value (Dart Sass module)

## Installation

```
$ npm install @gyugyu/map-pick-sass
```

## Example

```scss
@use '@gyugyu/map-pick-sass' as map-pick;

$map: (a: 1, b: 'foo', c: true);
$paths: a c;
$result: map-pick.pick($map, $paths); // (a: 1, c: true)
```
