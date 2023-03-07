```
$ yarn run webpack --mode
$ yarn run webpack --mode development
$ yarn run webpack --mode production
$ yarn run webpack --mode development --devtool false
```


```
$ yarn run webpack --config webpack.config.js
$ yarn run webpack --config webpack.dev.js
```

```
$ yarn  add --dev sass  sass-loader css-loader style-loader
```


# file-loader
- webpack5以降からAsset Modulesという機能で、file-loaderの機能が一部 webpack自体に盛り込まれたようだ。
  - そのため、file-loaderの設定は、一工夫必要。
  - https://hakozaru.com/posts/purge-webpacker-3
