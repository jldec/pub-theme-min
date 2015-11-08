# pub-theme-min

Minimal [pub-server](https://github.com/jldec/pub-server) theme with just the doc-layout and main-layout templates.

#### installation
To use this theme for a project on localhost, first `npm install` `pub-server` and `pub-theme-min`. The following command will run pub with this theme.

```sh
pub -t pub-theme-min
```

To make the theme permanent, use a `pub-config.js` with **`pub-theme-min`** in `pkgs`. E.g.

```js
module.exports = {
  pkgs:'pub-theme-min',
  sources:'./markdown',
  staticPaths:'./images'
}
```
