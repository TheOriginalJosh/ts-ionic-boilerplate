# ts-ionic-boilerplate
An attemp  to create a starter template for ionic and typscript, with gulp setup and ready to go along with the nessary d.ts files I'm using visual studio code, make sure you have ionic installed already.

in the project root directory:

1) setup sass for ionic

`ionic setup sass`

2) setup gulp &  gulp-typscript

`npm install gulp`

`npm install gulp-typescript`

you will need to install install gulp-tyscript which allows gulp to build form the tsconfig.json file, the gulp config is already setup. 
for more info: https://github.com/ivogabe/gulp-typescript

3) after that run 

`ionic serve`

gulp will monitor for any changes made to the TS and SASS files 
