# MicroCSS
Gulp module for encoding CSS files on the server, JavaScript library for decoding CSS files in the browser.

### Gulp Module Features
* Creates a hash table of most used strings of text found within file
* Replaces most used strings of text with pointers to hash table
* generates new file with hash table & file contents that contain reference pointers

### JavaScript Library Features
* Downloads CSS file for parsing
* Replaces reference pointers in CSS with text from hash table
* Creates `<style>` tag & renders decoded CSS onto the web page
