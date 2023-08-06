# PNG2JPG Converter 

This is a simple PNG to JPG converter. It allows the user to upload a PNG image and convert it to JPG.

## How it works

- The user can drag & drop a PNG file into the marked area or select it by clicking
- When clicking the "Convert" button, the PNG file is read and loaded into a canvas element
- The canvas is then converted and downloaded as a JPG file
- There is basic error handling in case no PNG file was selected

## Used technologies

- HTML, CSS and JavaScript
- FileReader API for reading the uploaded file 
- Canvas API for converting and creating the JPG file
- Basic responsive design using media queries

## Setup

The app requires no setup and can be opened directly in the browser. 

Simply open the index.html file in a modern browser.

## Possible improvements

- Allow file upload via drag & drop 
- Show upload progress and loading indicator during conversion
- More error handling, e.g. for oversized files
- Use a modern CSS framework for responsive design
- Perform conversion and download asynchronously in background

## License

The code is licensed under the MIT license and can be freely used.
