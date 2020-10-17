## Installation

Setup your folder and install gatsby, react and react-dom
```shell
mkdir my-docs
cd my-docs
yarn init

yarn add gatsby react react-dom
```

Install greenboard
```shell
yarn add gatsby-greenboard
```


Then add gatsby-greenboard to your `gatsby-config.js`. 

```javascript
module.exports = {
  plugins: [
    {
      resolve: "gatsby-greenboard",
      options: {},
    },
  ],
}
```
Now create your api documentation in `data/index.html.md`. You can check a sample format in [here](./example/data/index.html.md)


That's it, you can now run your gatsby site using

```shell
yarn gatsby develop
```

Build the production files

```shell
yarn gatsby build
```


## Usage
Fork this repo.

Clone the repo

Travese to the folder
```shell
cd greenboard
```

Install dependencies
```shell
yarn
```

To run example locally
```shell
yarn workspace example develop
```

To build example 
```shell
yarn workspace example build
```

To run the build files locally with serve
```shell
npm install -g serve

cd example/build
serve
```

To deploy example to github pages
```shell
yarn workspace example deploy
```

