# Vega: A Visualization Grammar

<a href="https://vega.github.io/vega/examples">
<img src="https://vega.github.io/vega/assets/banner.png" alt="Vega Examples" width="900"></img>
</a>

**Vega** is a *visualization grammar*, a declarative format for creating, saving, and sharing interactive visualization designs. With Vega you can describe data visualizations in a JSON format, and generate interactive views using either HTML5 Canvas or SVG.

For documentation, tutorials, and examples, see the [Vega website](https://vega.github.io/vega). For a description of changes between Vega 2 and later versions, please refer to the [Vega Porting Guide](https://vega.github.io/vega/docs/porting-guide/).

Are you using Vega in a web application built with a bundler such as [Webpack](https://webpack.js.org/) or [Browserify](http://browserify.org/)? If so, and you _do not need server-side rendering support_, you might prefer using [vega-lib](https://github.com/vega/vega-lib) to include Vega in your app. The vega-lib package also houses our general test suite.

## Build Instructions

For a basic setup allowing you to build Vega and run examples:

- Clone `https://github.com/vega/vega`.
- Run `yarn` to install dependencies for all packages. If you don't have yarn installed, see https://yarnpkg.com/en/docs/install. We use [Yarn workspaces](https://yarnpkg.com/lang/en/docs/workspaces/) to manage multiple packages within this [monorepo](https://en.wikipedia.org/wiki/Monorepo).
- Once installation is complete, use `yarn build` within the _vega_ or _vega-lib_ package to build output files. Use `yarn test` to run test cases for all packages. Use `yarn serve` to launch a local webserver and visit the `"test"` folder to browse test specifications.

This repository includes the website and documentation in the `docs` folder. To launch it, run `bundle install` and `bundle exec jekyll serve` in the `docs` folder. The last command launches a local webserver. Now, you can open [`http://127.0.0.1:4000/vega/`](http://127.0.0.1:4000/vega/) to see the website.

## Contributions, Development, and Support

Interested in contributing to Vega? Please see our [contribution and development guidelines](CONTRIBUTING.md), subject to our [code of conduct](CODE_OF_CONDUCT.md).

Looking for support, or interested in sharing examples and tips? Post to the [Vega discussion forum](https://groups.google.com/forum/#!forum/vega-js) or join the [Vega slack organization](https://bit.ly/join-vega-slack)!

Read about future plans in [our roadmap](https://docs.google.com/document/d/1fscSxSJtfkd1m027r1ONCc7O8RdZp1oGABwca2pgV_E/edit#).
