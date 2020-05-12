micro-app-one is only importing add.
micro-app-two is only importing multiply.
If you change add.js, nx will think both apps are affected.

`nx affected --target=build --files=libs/src/add.js`