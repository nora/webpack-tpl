Cloned from [gulp-webpack-starter](https://github.com/wwwebman/gulp-webpack-starter)

## Usage

Make sure that [Node.js](https://nodejs.org/) & [npm](https://www.npmjs.com/) installed. Install [yarn](https://yarnpkg.com) > `npm i yarn -g`.
`cd <catalog_you_want>` in your terminal and then:

```bash
git clone https://github.com/wwwebman/gulp-webpack-starter <my-project-name>
cd <my-project-name>
yarn install
yarn dev
```

> Yarn ???
> Yes, I recommend you to use yarn for fast dependencies installs, but `npm install` works just as well.

## All aliases

|`yarn <script>` or `npm run <script>`|Description|
|------------------|-----------|
|`dev`|Serves your App at `localhost:3000`. Run Browser sync and [HMR](https://webpack.github.io/docs/hot-module-replacement.html).|
|`production`|Compiles your App for production.|
|`deploy`|Push production version on remote server.|


## Clean
```bash
rm -rf .git
git init
git commit -m "init" 
```
* Remove [HTML](https://github.com/wwwebman/gulp-webpack-starter/tree/master/dev/html) and start you own project.
* Remove unused [SCSS](https://github.com/wwwebman/gulp-webpack-starter/tree/master/dev/sass/parts) & init [JS](https://github.com/wwwebman/gulp-webpack-starter/tree/master/dev/js/modules)


## Config
Your can make some modification in ./config.json file (e.g. ftp configuration)

---
Author - [webman.pro](http://webman.pro/)
