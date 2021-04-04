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
### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
