## Webpack

- The goal is to have a way to create and use Javascript modules with Gulp
- It turns out Webpack / CommonJS is ok for that, but for that only. Using the full power of Webpack is out of the goal.

### Basics

- http://webpack.github.io/docs/tutorials/getting-started/

1. With `require("./content.js")` you can import other JS modules from the project
2. With `require("!style!css!./content.css");` you can import CSS associated to a module


### Details

- http://blog.madewithlove.be/post/webpack-your-bags/

1. Webpack is very powerful but it's very complicated
2. Maybe standalone components should be created the React way, not the Webpack way


### With Gulp

- http://webpack.github.io/docs/usage-with-gulp.html
