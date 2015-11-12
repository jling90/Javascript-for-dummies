Introduction
============
Javascript is an [esolang](http://esolangs.org/wiki/esoteric_programming_language) commonly used in web development. 
The following snippet prints `hello world!` in Javascript. Newlines are included for readability and can be omitted.

    console.log(
    "\150"+
    (!!+[]+[])[~~!+[]<<~~(!+[]+!+[])]+
    (null+[])[~~!+[]|(++[[]][+[]]+~~!+[])]+
    ([]+!!+[])[++[[]][+[]]+~~!+[]]+
    ([]+{})[~~!+[]]+
    "\040\167"+
    ([]+{})[++[[]][+[]]]+
    ([]+!+[])[~~!+[]]+
    "\154"+
    ([]+void(0))[(++[[]][+[]]+~~!+[])<<~~(!+[]+!+[])]+
    "\041"
    )

