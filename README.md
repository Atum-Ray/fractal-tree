# fractal-tree
Javascript implementation of a repeating fractal tree design for fun

### Example Design
![Example design](http://i.imgur.com/9ZSK97P.png "Example design")

### Version
0.1.3

### Running Online
It is possible to run the web application directly from the repo:
https://cdn.rawgit.com/M-Roberts/fractal-tree/[commit_hash]/fractalTree.html

(Replace [commit_hash] with the full hash of the commit to be opened
e.g.: https://cdn.rawgit.com/M-Roberts/fractal-tree/45f42419a31c4068c9c7f398a96794f7f5f91223/fractalTree.html)

### Changelog

v0.1.3
  - Moved settings display ('Toto, I've a feeling we're not in canvas anymore.'), needs colour option
  - Slightly improved colour slider appearance

v0.1.2
  - Added primitive tree colour slider, needs better initialisation, etc.

v0.1.1
  - Added basic Mandelbrot set code (Daryl): needs to be tested
  - No longer fails whenever canvas size is changed

v0.1.0
  - Correctly loads fractal tree to screen canvas
  - Produces text display of main variables used in design
  - Fails whenever canvas size is changed

### TODO
  - Improve tree colour slider (fetch initial tree colour from slider starting values, edit colour of each slider to reflect RGB rather than just pale orange)
  - Add save and load functionality (use database for JSON variables? Encode them into GET var in URL? http://stackoverflow.com/questions/16686121/javascript-save-way-to-read-get-without-php)
  - Add JQuery inputs to change variables in real-time without page reload
  - Separate functions and default variable values by file; give JS files better names
  - Improve variable display, iterate over variable objects, write to actual text rather than on canvas
  - Adjust line width, branch length, colour, etc. according to generation of line drawn
  - Establish computational limits to prevent variables from being too large as to break
  - Get better scaling function which automatically adjusts to fit page no matter what the fractal tree design
  - Provide better commenting
  - Real-time Javascript function editing (if possible)
  - Create github.io page which gets latest commit hash, and redirects to/fetches from corresponding 'Raw Git' URL