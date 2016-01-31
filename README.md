# getClean : Colorful Backgrounds, Clear the Terminal, ... 
An Easy Way to get a Terminal Clear String. Useful for colored BackGrounds. (Node.JS).

Based on the source code of [this](https://www.npmjs.com/package/cli-clear) module.
## Usage
### Just a little soap...
```

    var getClean = require("getclean");
    process.stdout.write(getClean);
```
### Lets Paint it!!!
 Note: ANY Color mode is supported, but we're using [chalk](https://www.npmjs.com/package/chalk) to demonstrate:
 ```
    var getClean = require("getclean");
    process.stdout.write(chalk.blue(getClean));
```
    
