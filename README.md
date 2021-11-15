# How to use Discord.js v13 in Replit?

## Update Node.js v12 to Node.js v16 in Replit

Execute this script on the shell to install node.js v16:
```
npm init -y && npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH
```

Create a `.replit` file to execute node from the shell instead of the console.
```
run = "npm start"
```

Now, add a code to `package.json` file
```js
"scripts": {
    "start": "node ."
    }
```


**You can run the code!**
