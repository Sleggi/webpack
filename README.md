# Webpack + React + TypeScript base config

Building a boilerplate config

## Getting Started

1) .gitignore
2) src folder - input for app
3) build folder - output for app
4) ```
   npm init --y
   ```
5) index.html
6) ```
   npm install 'needed packages'
   ```
7) installing Dev dependencies for TypeScript
   ```
   npm install -D typescript @types/react @types/react-dom
   ```                                     
8) creating a config file for TypeScript - **tsconfig.json**. 
**Compiler for type checking and not for code transpilation**
9) in src **App.tsx** - root component
10) in src **index.tsx** - entry point
11) Installing **babel** to convert react and ts code into JS code
   ```
   npm install -D @babel/core  @babel/preset-env @babel/preset-react @babel/preset-typescript
   ```  
13) Babel configuration **.babelrc**
14) Webpack
   ```
   npm install -D webpack webpack-cli webpack-dev-server html-webpack-plugin
   ```  
15) To transpile JS files using babel and webpack 
    ``` 
    npm install -D babel-loader
    ``` 
16) webpack folder - **webpack.config.js** and populate it with base config
17) adding npm scripts in **package.json**
18) adding css loaders for webpack 
    ``` 
    npm install -D css-loader style-loader
    ``` 
    and then we add loaders into **webpack.config**
19) adding images, svg declarations, **declarations.d.ts**
then in **webpack.config** we need to specify loaders for ico,gif, png, jpg, etc from 
**'asset/resource'** webpack5
20) adding svg and fonts in **declarations.d.ts** and then in **webpack.config** we specify loaders
from **'asset/inline'** webpack5

