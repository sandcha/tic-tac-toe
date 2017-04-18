Tic Tac Toe example of React.js (id est [this tutorial](https://facebook.github.io/react/tutorial/tutorial.html#getting-started)) using [npm](https://docs.npmjs.com/getting-started/what-is-npm), [babel](https://babeljs.io) and [webpack](https://webpack.js.org).
Thanks to [codementor.io guide](https://www.codementor.io/tamizhvendan/beginner-guide-setup-reactjs-environment-npm-babel-6-webpack-du107r9zr).
<br/>
<br/>
### Install
In the project directory, install dependencies according to package.json file:

```
npm i
```

It will create the **./node_modules/** directory and update its content.
Then, generate webpack bundle file and its **./src/client/public/** directory: 

```
webpack -d
``` 

(or ```./node_modules/.bin/webpack -d``` )
<br/>
<br/>
### Run (development mode)
If you are making changes, run webpack in watch mode:

```
npm run dev
```

This works thanks to **package.json** scripts configuration.
<br/>
<br/>
### Miscellaneous

**package.json** file was created by:

```
npm init 
```

Its dependencies were updated by:

```
npm i webpack -S 
npm i react react-dom -S
npm i babel-core babel-loader babel-preset-es2015 babel-preset-react -S
```

**.babelrc** file could be deleted and its instructions added to **package.json** file:

```
  "babelrc": false,
  "babel": {
  	"presets": [
    	"es2015",
    	"react"
  	]
  }
```  
 
