[Web API Controversy](https://webapicontroversy.com)

**Shut down** due to lack of time to maintain + a general lack of interest from others as well as coming across as controversial in itself, requiring more time to navigate and research. Thanks for the interest! / Pelle

## Building

Running

```sh
$ npm install
```

```sh
$ npm run build
```

will build `index.html`. Commit that file to master. By pushing to the repository, the live version of the website is updated.

## Developing

```sh
$ npm run watch
```

Will continously rebuild `index.html` whenever `data.json` or `index.hbs` is changed.

## Data

All the data for the table is in `data.json`.

The browsers are defined in the `browser` property. The logo for the browser must be in the `logos` directory and must be named `${browser.tag}.svg`.

The APIs are defined in teh `api` property.

If a “Details” button is clicked, a “dialog” is openend, showing the contents of `partials/${api.tag}_${browser.tag}.html`.

## Based on

[Is Houdini Ready Yet?](https://ishoudinireadyyet.com)

## License
Apache 2

