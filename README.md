# Gulp Workflow


## Usage
    git clone https://github.com/techbusker/webworkflow

## Navigate inside the repo, open terminal and type:
    cd webworkflow

## Install all dependencies (**NOTICE: NodeJs with npm must be installed globally in your workstation**)
    sudo npm install

## Run it in the terminal and type:
    gulp


## File Structure

### Development Build
        src/           ---          source folder
        src/js/        ---          uncompressed js location
        src/img/       ---          raw image location
        src/sass       ---          scss file location


### Production Build
        dist/          ---          production folder
        dist/img       ---          compressed images
        dist/js        ---          compressed js
        dist/css       ---          minified css


## List of npm used

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