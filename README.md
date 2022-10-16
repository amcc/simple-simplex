# simple-simplex
A simplex noise implementation to use without modules in simple projects like p5js

Script by jwagner - https://github.com/jwagner/simplex-noise.js

# usage
include simplex.js in your project as a standard HTML script. Then initialise and use as below.

# 2D

```js
// initialize the noise function
const noise2D = createNoise2D();
console.log(noise2D(x, y));
```

# 3D
```js
const noise3D = createNoise3D();
console.log(noise3D(x, y, z));
```

# 4D
```js
const noise4D = createNoise4D();
console.log(noise4D(x, y, z, w));
```
# p5js example
Here's an example of simplex noise in the p5js editor, adapted from a Daniel Shiffman tutorial:
https://editor.p5js.org/amcc/sketches/E4Td8bDbW
