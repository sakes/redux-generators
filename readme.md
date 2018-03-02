# DO NOT USE - An Experimental Fork of Redux Generators

This is not a supported version of redux-generators, just a place to experiment with customized templates. Please refer to bpxl-labs if looking for [redux-generators](https://github.com/bpxl-labs/redux-generators).

### Goals of this fork
- provide a place to experiment with generating redux / react boierplate via templates
- codify common patterns to handle common redux / react boilerplate

# Redux Generators Readme

Can be found at [redux-generators](https://github.com/bpxl-labs/redux-generators).

# Feel Free to Reference

Feel free to reference this fork if looking for ideas on how to add your own custom templates to redux-generators.  Early commit messages should provide direction.

### Basic description of how I am running my own version 
- Fork [redux-generators](https://github.com/bpxl-labs/redux-generators)
- git clone your fork of redux-generators
- modify package.json so that your forked code base will register uniquely with your npm [reference](https://github.com/sakes/redux-generators/commit/db080ddbf99b25879d200772cd7207412463db6d)
- run `$ npm link` from the root directory of your forked code base

### Examples
- add a custom template / command [Hello Example](https://github.com/sakes/redux-generators/commit/670029e13470a09f69e1e4d99e11e7ffbe8e29f2)
