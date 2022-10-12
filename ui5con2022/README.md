# `wdi5` workshop at UI5con 2022

<center>
<img src="https://github.com/js-soft/wdi5/raw/main/docs/img/wdi5-logo-small.png" alt="wdi5 logo!">
</center>

Here are the sources for the `wdi5` workshop at UI5con 2022.

## prerequisites

please have this installed on your 'puter:

- Node >= 16 &rarr; <https://nodejs.org/en/>
- `git` &rarr; <https://git-scm.com>
- Docker (desktop) &rarr; <https://www.docker.com/products/docker-desktop/>
- Google Chrome &rarr; <https://www.google.com/intl/en_us/chrome/>
- an IDE/Editor (we'll demo with VS Code)

## prep

This is an `npm`-based mono repo.  
:warning: **So at least Node >= 16 with npm >= 7 is needed**.

It consits of three types of apps:

- plain JS-based UI5 app
- TypeScript-based UI5 app, incl UI5 Webcomponents
- Fiori Elements app

In the `/` of the project, doing an...

```shell
$> npm install
```

...will install all dependencies and modules for all three applications in one Go.

## run

It's the same approach for all three apps:

- cd `$app`
- Terminal 1: `npm run serve`  
  starts the ui5 tooling serving the app
- Terminal 2: `npm run wdi5`  
  starts the `wdi5`-tests for the app
