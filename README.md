Make sure you have node.js installed

Install all dependencies, as specified in package.json, then, install the gulp build tool:

cd <potree_directory>
npm install --save
npm install -g gulp
npm install -g rollup
Use the gulp watch command to

create ./build/potree
watch for changes to the source code and automatically create a new build on change
start a web server at localhost:1234. Go to http://localhost:2000/examples/viewer.html to test the examples.
gulp watch