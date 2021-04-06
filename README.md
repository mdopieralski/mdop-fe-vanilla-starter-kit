# mdop-fe-vanilla-starter-kit

Starter kit for non-framework front-end projects.

- webpack & webpack-dev-server as build tool & local environment.
- tailwind & purge-css as UI layer kept tidy & clean.
- eslint & eslint-plugin-html to keep code bright & shiny.
- husky & commitizen to keep repo & changelog in order.

------------
### Prerequisites

- **Node**: >=v15.13.0
------------

### Scripts
package.json script  | Description
------------- | -------------
`build` | Prepare build in dist folder.
`commit` | Runs [git-cz](https://github.com/commitizen/cz-cli) for clear commits naming.
`dev` | Runs development mode on local server server.
`lint` | Runs [eslint](https://eslint.org/).
------------

### Contributing

There's pre-commit git-hook applied with [lint-staged](https://github.com/okonet/lint-staged) to keep code tidy & shiny.
For branching model, please use [git-flow](https://danielkummer.github.io/git-flow-cheatsheet/).


------------
### Versioning

[SemVer](http://semver.org/)