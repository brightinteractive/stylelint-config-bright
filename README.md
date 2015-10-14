# stylelint-config-bright

Simple in-house [styelint](https://github.com/stylelint/stylelint) config used by Bright Interactive

## Install

```console
$ npm install stylelint-config-bright
```

## Usage

Using Gulp to lint your files via postcss

```js
var brightconfig = require('stylelint-config-bright');

gulp.task('csslint', function() {
    return gulp.src('css/file/to/lint.css')
        .pipe(postcss([stylelint(brightconfig)]));
});
```



## [License](LICENSE)


