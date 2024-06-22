# Blockly SGL.js https://vroby65.github.io/blockly-sgljs/

![immagine](https://github.com/vroby65/blockly-sgljs/assets/6366632/01453f08-0a1a-487b-9a3a-653d93e8acc9)


This project provides a simple block-based coding environment using HTML, JavaScript, and the SGL.js library.

## Features

- Block-based programming interface
- Easy-to-use UI
- Integration with SGL.js library

## Requirements

- Modern web browser
- Basic knowledge of HTML and JavaScript

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/vroby65/blockly-sgljs.git
    ```

2. Open the `index.html` file in your web browser.

## Usage

- Drag and drop blocks to create your code.
- Click on "Run" to execute the code.

## Getting Started with Blockly-SGLJS
Blockly-SGLJS is a Blockly-based program that executes JavaScript code. The program consists of two files: index.html and sgl.js. It can be used with a browser on your PC or installed on a server and accessed over the network. It does not save anything on the server side; programs must be loaded and saved on your PC. Additionally, it provides persistence of programs using the browser's local storage.

## Features
- Simplified JavaScript syntax
- update function executed 60 times per second
- Commands executed at startup
- Graphical commands targeting surfaces
- Special display variable for canvas
- Keyboard and mouse input handling
- Save and load programs
- Export programs as standalone HTML files


## Basic Usage
Creating a Surface

```javascript
var mySurface = surface(800, 600);
```
Setting the Display

```javascript
setdisplay(width,height);
```
Drawing on the Surface

```javascript
/ Example: Drawing a rectangle
rect(mySurface, 50, 50, 200, 100, color);

Handling Input

```javascript
function update() {
    if (keydown('a')) {
        // Do something when 'a' key is pressed
    }
}
```
Saving and Loading Programs

Use the provided interface to save and load your programs.
Export programs as HTML files for standalone use.
Exporting Programs

Export your program as an independent HTML page that requires sgl.js to function.
By following these steps and utilizing the provided commands, you can create interactive graphical applications using Blockly-SGLJS.


## Project Structure

- `index.html`: The main HTML file.
- `sgl.js`: The SGL.js library.
- Require CDNJS repository
  
## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any questions or suggestions, please open an issue on GitHub.
