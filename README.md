# Salt Examples

 - [torque-example](./torque-example) - illustrates using Salt to build TileJSON datasets compatible with [CartoDB's Torque](https://github.com/CartoDB/Torque) library.

## Dependencies
To run the example projects your development environment will need to have the following installed:

 - Docker
 - Java compiler
 - Gradle
 - Node + npm

## Running Examples
Examples generally have two phases: 1) tile data generation, 2) web-based viewer of the result. Tile generation relies on a Docker container running Apache Spark to simplify running examples on your local machine. To build this container for use in all examples, run:

```
$ docker build -t docker.uncharted.software/salt-examples .
```

Please see README.md files in each example directory for further instructions.