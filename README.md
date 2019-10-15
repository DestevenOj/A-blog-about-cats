# A-blog-about-cats
Vanilla Js blog site



**************************************

*. create a repo and clone into it in github
*. cd to the project folder
*. npm init - to initialize the project
*. npm install - install packages to your project
*. From your project directory, run:   npm install babel-cli babel-preset-env --save-dev
   [installs Babel as a development dependency for our projec]

*. Create a file in your project directory called  .babelrc :
   add this line to file: {
 			   "presets": ["env"]
			}

*. Ask Babel to transpile  scripts.js  and save the output to  scripts.babel.js : npx babel scripts.js --out-file scripts.babel.js
*****The  npx  command allows us to run locally installed packages!

*.******  Now if you open  scripts.babel.js , you will see that our code has been transformed! Try importing our new  js  file into index.html instead of  scripts.js  and see if it works.

