utf8.js
================

Convert JavaScript strings to UTF8 byte arrays.

Usage
----------------

    // convert string to utf8 bytes
    var bytes = utf8.stringToBytes('string to convert');
    console.log(bytes);

    // convert utf8 bytes back to a string
    var str = utf8.bytesToString(bytes);
    console.log(str);
