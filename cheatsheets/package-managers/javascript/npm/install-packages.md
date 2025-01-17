# Install packages

You must create a `package.json` file with `npm init` before you can run installs in a project.


## Install

See cheatsheets for:

- [npm install][] command.
- [npm ci][] command for production and automated deploys.

[npm install]: {% link cheatsheets/package-managers/javascript/npm/commands/install.md %}
[npm ci]: {% link cheatsheets/package-managers/javascript/npm/commands/ci.md %}


## View

You can get info on a package about it from the NPM registry.

```sh
$ npm view @vue/cli
```

```
@vue/cli@4.5.11 | MIT | deps: 35 | versions: 140
Command line interface for rapid Vue.js development
https://cli.vuejs.org/
...
dist-tags:
latest: 4.5.11       next: 5.0.0-alpha.4
```
