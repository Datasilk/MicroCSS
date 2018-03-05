# MicroCSS
Gulp module for encoding CSS files on the server, JavaScript library for decoding CSS files in the browser.

### Gulp Module Features
* Creates an array of most used strings of text found within a CSS file
* Replaces most used strings of text with index pointers (e.g. `<1<`)
* generates new file with string array & file contents that contain reference pointers to array

### JavaScript Library Features
* Downloads CSS file for parsing
* Replaces reference pointers in CSS with text from hash table
* Creates `<style>` tag & renders decoded CSS onto the web page
