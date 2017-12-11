# Gulp.js Sass, Pug, ES6 starter
This is a simple starter for Sass, es6, pug.

## Instructions:
	$ npm install
	$ npm start       -> for starting livereload server
	$ npm run build   -> create and reduce files in ./dist 

## Directories:
### <strong>Development</strong> 
<pre>
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
            
</pre>

### <strong>Production</strong> 
<pre>
    ./dist
        |_ assets
            |_index.html
            |_img/
            |_fonts/
            |_js/
                |_bundle.js  <i>// merge all files from <strong>src/assets/js/*</strong></i>
            |_css/                                                       
                |_ main.css
</pre>
