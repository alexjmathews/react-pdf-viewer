This folder demonstrates how to bundle React PDF viewer with [Webpack](https://webpack.js.org)

1. Install the dependencies

~~~
npm install
~~~

2. Build

~~~
npm run build
~~~

3. Running locally

~~~
npm run dev
~~~

Visit http://localhost:8001/. You can change the port `8001` in the `devServer.port` section of the webpack setting file: 

~~~ javascript
// webpack.config.js

module.exports = {
    ...
    devServer: {
        port: 8001,
    },
};
~~~
