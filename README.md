# Coursera : Image and video processing: From Mars to Hollywood with a stop at the hospital #

This is my workshop for the class [Image and video processing: From Mars to Hollywood with a stop at the hospital](https://www.coursera.org/course/images)

Since I have no professional use for Mathlab, I will be using client-side Javascript and Canvas to do the exercises and practice.

Feel free to use, fork and share the code.

## Demo ##
[http://26medias.github.io/coursera-image-processing/build/index.html](http://26medias.github.io/coursera-image-processing/build/index.html)


## Structure ##
`/bin` Build script (Require NodeJS)

`/build` The output of the build process.

`/src` The sources. 

## How to edit and build ##
1. The main layouts are located in `/src/templates/`
2. The pages are located in `/src/pages/`. Each directory contains a `page.json` file describing what files to build, using what layout, and which dependencies (JS/CSS, which are managed by Bower and located in `/src/bower_components/`). Create/edit your pages, edit the corresponsing `page.json`.
3. Execute `node bin/build.js` or use one of the build script located in `/build` (`/build/build-win.bat` or `/build/build-unix.sh`). Don't forget to install the dependencies first (execute `npm install` from `/build`)
4. Launch your built static site from `/build`.

## License ##
Copyright (c) 2014 twenty-Six Medias, Inc

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
