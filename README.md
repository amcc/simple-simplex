# simple-simplex
A simplex noise implementation to use without modules in simple projects like p5js

Script by https://github.com/jwagner @jwagner
https://github.com/jwagner/simplex-noise.js

# usage

2D
// initialize the noise function
```js
const noise2D = createNoise2D();
console.log(noise2D(x, y));
```
3D
```js
const noise3D = createNoise3D();
console.log(noise3D(x, y, z));
```
4D
```js
const noise4D = createNoise4D();
console.log(noise4D(x, y, z, w));
```
