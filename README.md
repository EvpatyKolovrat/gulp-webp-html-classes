# gulp-webp-html

## Example
```html
// Input
<img src="/img/tmp/catalogImage.jpg">

// Output
<picture class="class" >
    <source srcset="/img/tmp/catalogImage.webp" type="image/webp">
    <img class="class" src="/img/tmp/catalogImage.jpg">
</picture>
```
## Install
```bash
npm i --save-dev gulp-webp-html-classes
```
## Usage
```javascript
var webpHTML = require('gulp-webp-html-classes');

gulp.task('html',function(){
    gulp.src('./assets/**/*.html')
        .pipe(webpHTML())
        .pipe(gulp.dest('./public/'))
});
```
"# gulp-webp-html-classes" 
