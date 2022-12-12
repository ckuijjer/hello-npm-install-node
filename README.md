# hello-npm-install-node

Playing with https://www.npmjs.com/package/node

```
npm install -D node@lst
```


```
🦃 hello-npm-install-node $ node index.js 
v16.16.0
🦏 hello-npm-install-node $ npm run start

> hello-npm-install-node@1.0.0 start
> node index.js

v16.13.2

🌰 hello-npm-install-node $ npx node index.js                                                           
v16.13.2
```

* Note that current Node.js LTS is 18.12.1, while this installs 16.13.2 → don't use `node@lts`
* Use `npm install -D node@v16-lts` to get the latest v16 LTS
* Use `npm install -D node@v18-lts` to get the latest v18 LTS
* Does add quite some node_modules, e.g. 77mb for 16.13.2 and 130mb for 18
