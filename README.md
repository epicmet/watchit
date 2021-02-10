# Introduction
_watchit_ is a practice with nodejs from [udemy javascript course](https://www.udemy.com/course/javascript-beginners-complete-tutorial/)

With this application on your system you track the changes in your nodejs javascript file, in otherword this application will run your code in the system terminal and if you make some changes and save it, this app will get those changes and run the file immediately. Somthing like **nodemon** command.
## Usage
if you want to use this app you should install [caporal](https://www.npmjs.com/package/caporal), [chokidar](https://www.npmjs.com/package/chokidar), [lodash.debounce](https://www.npmjs.com/package/lodash.debounce) and [chalk](https://www.npmjs.com/package/chalk) npm package by just simply install them in your directory with this syntax :
```console
npm install NAME_OF_THE_PACKAGE
```
And also require **fs** and **child_process** form nodejs api.

## Note
This app will work on windows system and may or may not get some errors if you try to run it on linux or macOS
