# talk-of-europe
Visualisation of Talk-of-Europe data using Pengine and the Swish-Prolog backend

It is very simple to get this example to work in your own environment because you only need a webserver to host html, css, png and js files. 

First, the index.html page loads the required libs and css. After that 
* the Pengine.js makes connections to the [SWISH Pengine backend](http://linkedpolitics.ops.few.vu.nl/pengine), 
* informs it which [prolog file](http://linkedpolitics.ops.few.vu.nl/swish/p/visual2.pl) to use, 
* does some prolog queries, 
* fetches the results 
* and displays them.

