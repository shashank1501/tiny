# tiny
![npm](https://img.shields.io/npm/v/tiny?label=tiny&style=plastic)

It is a tiny example package
# install

npm install @shashank.map/tiny

# usage
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
