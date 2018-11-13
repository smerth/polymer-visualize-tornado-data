# Polymer Visualize Tornado Data


A Polymer and Google Web Components app to visualize thousands of data points over an interactive Google Map, the app loads data, passes it into WebGL, and then allows zooming in on the map.

![App Screenshot](https://raw.githubusercontent.com/smerth/polymer-visualize-tornado-data/master/Screenshot.png)



## Install

You'll need to have node.js, polymer-cli and yarn installed to begin

Install bower dependancies

```bash
polymer install
```

Install gulp to deploy to gh-pages

```bash
yarn install
```



## Develop

```bash
polymer serve
```



## Build

to build the compiled app

```bash
polymer build
```

to serve the built app

```bash
polymer serve build/default
```



## Deploy to gh-pages

Set up your codebase on github and then run

```bash
gulp deploy
```



## Demo

[Tornado Data for the United States 1950-2014](https://smerth.github.io/polymer-visualize-tornado-data/)



## References

[Data Visualization Using Polymer and WebGL](https://codelabs.developers.google.com/codelabs/polymer-webgl/index.html?index=..%2F..%2Findex#0)

