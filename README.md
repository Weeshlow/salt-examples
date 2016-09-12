# Salt Examples

> Examples for [Salt](https://github.com/unchartedsoftware/salt)

**Please be sure to check out the release tag matching the version of Salt you intend to use**

 - [png-example](./png-example) - illustrates using Salt to build .png image datasets compatible with any TMS visualization library.

 - [bin-example](./bin-example) - illustrates using Salt to build byte file datasets which utilize client-side heatmap rendering using [Leaflet's TileLayer.Canvas](http://leafletjs.com/reference.html#tilelayer-canvas) library.

 - [torque-example](./torque-example) - illustrates using Salt to build TileJSON datasets compatible with [CartoDB's Torque](https://github.com/CartoDB/Torque) library.

 - [path-example](./path-example) - similar to [bin-example](./bin-example), but illustrates rendering lines instead of points

 - [hierarchical-pie-example](./hierarchical-pie-example) - illustrates using Salt and D3.js to build a non-2D-spatial visualization of inherently hierarchical data

## Dependencies

To run the example projects your development environment will need to have the following installed:

 - Docker
 - Java compiler
 - Gradle
 - Node + npm

## Running Examples

Examples generally have two phases:
1) tile data generation
2) web-based viewer of the result

Please see README.md files in each example directory for further instructions.

### Using Windows?

Windows and Docker don't always play nicely together when it comes to volume mounting. Some tips:

 - Make sure you have \*NIX line endings on all the files in your working copy. Set `$ git config core.autocrlf false` and check out a fresh copy of the `salt-examples` codebase.
 - If all else fails, try virtualizing a Linux environment
