# MARS-MIPS-Cache-Tester
Randomly writing to memory and using tools within MARS IDE to compare different cache mapping methods

In this project we needed to write to memory randomly (and do it enough times to fill up the cache) to be able to compare the different cache mapping techniques.  The trick was to allocate memory first and then do the writing to some random offset inside the variable.  It would have been smart to use the "spaces" datatype(?) instead of copy/pasting a ton of random data to fill up the data portion.  

These are: <br />
1) Direct mapped <br />
2) Set-associative mapped <br />
3) Fully-associative <br /> <br />

![mars_proj1](https://s14.postimg.org/dsz4y3r4d/mars_proj1.png) <br />

![mars_proj2](https://s14.postimg.org/4zctuqtjh/mars_proj2.png)
