# [Data Visualization Using Polymer and WebGL](https://codelabs.developers.google.com/codelabs/polymer-webgl/index.html?index=..%2F..%2Findex#0)

Display tornadoes on Google Maps - DONE 😉 - publish on github pages...

In this codelab, you’ll create a visualization of thousands of data points over an interactive Google Map, taking advantage of Polymer and some [Google Web Components](https://elements.polymer-project.org/browse?package=google-web-components) to easily cobble together a pipeline to load data, pass it into WebGL, and then manipulate it in real time.

---

Deploying:
After running polymer build check point-overlay.  It is missing the json data... i think this is because polymer build only deals with html and js files...
So you need to manually copy ove the json data...
run gulp deploy again.  
You need to do this each time you run gulp build.

--- 
on gh-page there is a ton of css errors...  is polymer build not dealing with css properly?
on gh-pages missing polymer-1-visualize-tornado-data/shared-bundle.html don't know what that refers to but this app was built in Chrome Dev Editor... is it something from that environment?    
