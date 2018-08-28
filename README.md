# hello-nodejs-addon-with-cmakejs

This is an example project that compiles with `cmake-js`, not `node-gyp`.

`cmake-js` is a nodejs native addon build tool that does not depend on `node-gyp` (thus, idependent from Pyton 2.x).

`cmake-js` + N-API leads the new age of NodeJS native addons!

## How to build

* build: `npm run build` (it just calls `cmake-js`)
* test: `npm run test`

## See Also

* cmake-js: https://github.com/cmake-js/cmake-js
* N-API: https://nodejs.org/api/n-api.html
