# Introduction

Maybe in the package.json of your project you have a content like this:

```json
{
  "name": "01",
  "version": "1.0.0",
  "description": "",
  "main": "src/index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
```

To run the script that you have above in the node "main" (src/main.js), you can use the following command in the same folder where your package.json is located:

```sh
node .
```


# node --watch

In Node.js 18+ you can use the following command to watch for changes in your files ("." is an example in the next command):

```sh
node --watch .
```

This will run your script and watch for changes in your files (live reload).