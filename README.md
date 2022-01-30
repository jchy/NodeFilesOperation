### To Run this project 
- Clone it onto your system
- Run the following command in the Assignment_10 directory
```js
  nodemon writeFile.js
  or 
  nodemon readFile.js
```
## Different ways of reading of file in Node JS
### 1. Synchronous methods: 
- Synchronous functions block the execution of the program until the file operation is performed. These functions are also called blocking functions. The synchronous methods have File Descriptor as the last argument. File Descriptor is a reference to opened files. It is a number or a reference id to the file returned after opening the file using fs.open() method of the fs module. All asynchronous methods can perform synchronously just by appending “Sync” to the function name.
### 2. Asynchronous methods:
- Asynchronous functions do not block the execution of the program and each command is executed after the previous command even if the previous command has not computed the result. The previous command runs in the background and loads the result once it has finished processing. Thus, these functions are called non-blocking functions. They take a callback function as the last parameter.
### Advantages of using asynchronous file operations over synchronous file operations
- Asynchronous functions are generally preferred over synchronous functions as they do not block the execution of the program whereas synchronous functions block the execution of the program until it has finished processing
