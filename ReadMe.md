PALO: PAge LOad Emulator
==========
This project emulates a web page load while keeping the compute portion of the page constant.

Setup
----------
Extract web page dependencies using a tool like [WProfX](https://github.com/jnejati/WProfX).


Running
----------

Steps:
1. Change the ```dataFile``` variable in the javascript to a link to file retreived from WProfX recording and analysis
2. Change the ```paralleize``` and ```scaling factor``` variables
3. Load ```test.html``` in a browser and see the emulation time
