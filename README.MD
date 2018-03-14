# html-sass-webpack-seed
This is seed project is created based on the tutorial https://www.youtube.com/watch?v=y_RFOaSDL8I
It lets use multiple html pages with webpack. it comes with bootstrap 4 shipped and ready to use.

## Installation


Clone this project and then run `npm install` to setup project dependencies.

Each time you add an html to your project you must add it to the webpackconig, for example if you add `about.html` to the `src` folder you should add this code to your plugins in the webpackconfig:

```javascript
  new HtmlWebpackPlugin({
            template: 'src/about.html',
            filename:'about.html'
        }),
```
