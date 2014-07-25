gulp-resx2js
============

Converts Visual Studio resx files to JavaScript objects.

## Install

```
npm install gulp-resx2js
```

## Usage

```javascript

var gulp = require('gulp');
var resx2js = require('gulp-resx2js');

gulp.taks('resx', function(){
	gupl.src('./Resources/*.resx')
		.pipe(resx2js())
		.pipe(gulp.dest('./build'));
});

```

## License

MIT license - [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)
