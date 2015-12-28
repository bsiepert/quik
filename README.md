Quik
====
A quick way to prototype apps with React and Babel.

Setting up the tooling required to work on a modern day web app is hard, and makes quick prototyping much more difficult than it should be. Quik is a quick way to prototype a React application without any kind of setup.

## Installation and usage

First, install the npm package globally.

```sh
npm install -g quik
```

Now open the Terminal in any directory and run the following,

```sh
quik
```

It'll start a simple server which will serve the files in the current directory.

You can provide a port as an argument if you want to use a different port. For example, to run the server in the port `8008`, run,

```sh
quik 8008
```

You can include any ES2015 file in a script tag in an HTML file and the script will be transpiled to ES2015 on the fly. You can use ES2015 modules to require other scripts as well.

You can also `import` the following packages by default without any `npm install`,

* radium
* react
* react-dom
* react-redux
* redux

To generate a sample project with an HTML file and a script, run the following in a Terminal,

```sh
quik init AwesomeProject
```

This is just for your convenience and is completely optional.