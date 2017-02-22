[![npm][npm]][npm-url]
[![deps][deps]][deps-url]
[![test][test]][test-url]
[![coverage][cover]][cover-url]
[![chat][chat]][chat-url]

<div align="center">
  <!-- replace with accurate logo e.g from https://worldvectorlogo.com/ -->
  <img width="200" height="200"
    src="https://cdn.worldvectorlogo.com/logos/babel-10.svg">
  <a href="https://github.com/webpack/webpack">
    <img width="200" height="200" vspace="" hspace="25"
      src="https://worldvectorlogo.com/logos/webpack.svg">
  </a>
  <h1>Webpack Babel Preset</h1>
  <p>Provides Webpacks's es2015 Babel preset.<p>
</div>

<h2 align="center">Install</h2>

```bash
npm i -D babel-preset-webpack
```
asdf
<h2 align="center">Usage</h2>

### Via `.babelrc`

**.babelrc**

```json
{
  "presets": ["webpack"]
}
```

### Via CLI

```sh
$ babel script.js --presets webpack 
```

<h2 align="center">Comparison Demo</h2>

The repo includes a copy of the `extract-text-plugin` for the purposes of vetting transpiled output to assist in the selection of ECMA features for this preset.

`./demo-app/extract-text-orig`: Original application code without modification.

`./demo-app/extract-text-babel`: es6 features added ( this is a wip ) without making significant changes to code structure.

### Run the comparison build

```sh
$ npm run build
```

_Babel will output transpiled code & sourcemaps to `./dist`_

<h2 align="center">Maintainers</h2>

<table>
  <tbody>
    <tr>
      <td align="center">
        <img width="150" height="150"
        src="https://avatars2.githubusercontent.com/u/8420490?v=3&s=150">
        </br>
        <a href="https://github.com/d3viant0ne">Joshua Wiens</a>
      </td>
      <td align="center">
        <img width="150" height="150"
        src="https://avatars3.githubusercontent.com/u/166921?v=3&s=150">
        </br>
        <a href="https://github.com/bebraw">Juho Vepsäläinen</a>
      </td>
    </tr>
  <tbody>
</table>


[npm]: https://img.shields.io/npm/v/babel-preset-webpack.svg
[npm-url]: https://npmjs.com/package/babel-preset-webpack

[deps]: https://david-dm.org/webpack-contrib/babel-preset-webpack.svg
[deps-url]: https://david-dm.org/webpack-contrib/babel-preset-webpack

[chat]: https://img.shields.io/badge/gitter-webpack%2Fwebpack-brightgreen.svg
[chat-url]: https://gitter.im/webpack/webpack

[test]: http://img.shields.io/travis/webpack-contrib/babel-preset-webpack.svg
[test-url]: https://travis-ci.org/webpack-contrib/babel-preset-webpack

[cover]: https://coveralls.io/repos/github/webpack-contrib/babel-preset-webpack/badge.svg?branch=master
[cover-url]: https://coveralls.io/github/webpack-contrib/babel-preset-webpack?branch=master
