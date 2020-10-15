# Gulp.js Sass, Pug, ES6 starter
This is a simple starter for Sass, es6, pug.

## Instructions: 
- `$ npm install` - install packages  
- `$ npm start` - run livereload server  
- `$ npm run build` - create and reduce files in _./dist_  

## Directories:  
### Development  
``` javascript
    ./src
        |_ assets
            |_index.pug
            |_img/
            |_fonts/
            |_js/
            |_layout/
               |_footer/
               |_header/
               |_main/
            |_sass/
                |_ _custom.sass
                |_ _reset.sass
                |_ _variables.sass
                |_main.sass
            
```

### Production  
```javascript
    ./dist
        |_ assets
            |_index.html
            |_img/
            |_fonts/
            |_js/
                |_bundle.js // merge all files from src/assets/js/
            |_css/                                                       
                |_ main.css
```
