## drop-console-webpack-plugin
#### A webpack plugin for removing console and supporting webpack4
## Installation
```
npm install drop-console-webpack-plugin --save
```
## Usage
```
    const DropConsoleWebpackPlugin = require('drop-console-webpack-plugin')

    plugins: [
        new DropConsoleWebpackPlugin(),
    ]
```
## Options
Name | type | default | Description
--------- | ------- | ------ | ---------------------
drop_log | Boolean | true | remove console.log(...)
drop_info | Boolean | true | remove console.info(...)
drop_warn | Boolean | false | remove console.warn(...)
drop_error | Boolean | false | remove console.error(...)
## Code
```
new DropConsoleWebpackPlugin({
    drop_log    : true, 
    drop_info   : true,
    drop_warn   : false,
    drop_error  : false,
})
```
