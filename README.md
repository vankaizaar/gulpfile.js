# Gulpfile.js
Sample gulpfile.js settings

## Features
1. Sass
   * Compiling
   * Autoprefixer
   * Sourcemaps
   * Minification 
2. JS
   * Compiling
   * Sourcemaps 
   * Uglify
3. Images
   * Compiling
   * Compressing
4. HTML
   * Compiling
5. Fonts
   * Compiling
6. Browser Sync
   * Auto reload page
   
## Project
```
+-- node_mmodules/  
+-- build/  
|     +-- css/  
|     +-- js/  
|     +-- img/  
|     +-- fonts/  
|     +-- index.html  
+-- src/  
|     +-- style/  
|     |     +-- libs/  
|     |     +-- partials/  
|     |     +-- main.scss  
|     +-- js/  
|     |     +-- libs/  
|     |     +-- partials/  
|     |     +-- main.js  
|     +-- img/  
|     +-- fonts/  
|     +-- index.html  
+-- gulpfile.js  
+-- package.json
```

## Setup
Run `npm instasll` to install packages

## Start
Run `gulp` and start developing

## All gulp tasks
* `gulp` or 'gulp default' - default task, builds assets, starts watching directories for changes and reload browser
* `gulp build` - rebuilds all assets
* `gulp watch` - starts watching directories for changes
* `gulp webserver` - run local web server
* `gulp clean` - delete build folder
* `gulp html:build` - html compilation
* `gulp style:build` - scss compilation
* `gulp css:build` - css compilation from ./libs
* `gulp image:build` - image compilation
* `gulp fonts:build` - fonts compilation

## License
MIT License

Copyright (c) 2018 Vladislav

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
