# FIGLET

FIGlet is a computer program that generates text banners, in a variety of typefaces, composed of letters made up of conglomerations of smaller ASCII characters (see ASCII art). The name derives from "Frank, Ian and Glenn's letters

## FIGLET INSTALL Command

### Install
npm install figlet

### Simple usage code

"var figlet = require("figlet");

figlet("Hello World!!", function (err, data) {
  if (err) {
    console.log("Something went wrong...");
    console.dir(err);
    return;
  }
  console.log(data);
});"

### Links
For more information, please visit: https://www.npmjs.com/package/figlet
