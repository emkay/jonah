jonah
=====

Hex to Ascii, Ascii to Hex

## Usage
    var jonah = require('jonah');

    jonah.hex('hello'); // returns 68656C6C6F  
    
    jonah.ascii('68656C6C6F'); // returns hello
    
    jonah.nesHex('hello world'); // returns $68,$65,$6c,$6c,$6f,$20,$77,$6f,$72,$6c,$64,$00
