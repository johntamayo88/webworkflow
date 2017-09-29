# Gulp Workflow

### Usage
    git clone https://github.com/techbusker/webworkflow

### Navigate inside the repo, open terminal and type:
    cd webworkflow

### Install all dependencies (**NOTICE: NodeJs with npm must be installed globally in your workstation**)
    sudo npm install

### Run it in the terminal and type:
    gulp


## File Structure

    |—— webworkflow
    |       |         ### Production Build
    |       |—— dist/         ——     distribution folder
    |       |—— dist/img      ——     raw images
    |       |—— dist/js       ——     raw javascripts
    |       |—— dist/css      ——     
    |       |
    |       |
    |       |        ### DevelopmentBuild
    |       |—— src/          ——     source folder
    |       |—— src/js/       ——     minified js
    |       |—— src/img/      ——     minified images
    |       |—— src/sass      ——     sass
    |
    |—— .gitignore
    |—— gulpfile.js
    |—— package.json
    |—— README.md

### List of npm used

    gulp
    gulp-sass
    gulp-sourcemaps
    gulp-autoprefixer
    gulp-imagemin
    gulp-useref
    gulp-if
    gulp-uglify
    gulp-babel
    gulp-uncss
    browser-sync