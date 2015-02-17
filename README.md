To reproduce:

```bash
npm install
npm install -g browserify
browserify main.js -o bundle.js
```

This will produce error:

```
Error: Cannot find module 'tether' from '/Users/kbru/code/futurice/tether-browserify-bug'
    at /Users/kbru/.nvm/v0.11.13/lib/node_modules/browserify/node_modules/resolve/lib/async.js:50:17
    at process (/Users/kbru/.nvm/v0.11.13/lib/node_modules/browserify/node_modules/resolve/lib/async.js:119:43)
    at /Users/kbru/.nvm/v0.11.13/lib/node_modules/browserify/node_modules/resolve/lib/async.js:128:21
    at load (/Users/kbru/.nvm/v0.11.13/lib/node_modules/browserify/node_modules/resolve/lib/async.js:60:43)
    at /Users/kbru/.nvm/v0.11.13/lib/node_modules/browserify/node_modules/resolve/lib/async.js:66:22
    at /Users/kbru/.nvm/v0.11.13/lib/node_modules/browserify/node_modules/resolve/lib/async.js:21:47
    at Object.oncomplete (fs.js:97:15)
```
