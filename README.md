# rxtx2jssc
little functional bridge rxtxcomm and jssc libraries.

In one project, I had to work with some code that doesn't work very well on Windows 8, so I developed this tiny library that allows java applications with rxtxcomm library to use jssc library with no modifications on your original code.


* Instructions:

- remove the old rxtxcomm jar from your project
- add rxtx2comm jar
- add jssc jar
- enjoy!
 

* How it works?

It's quite simple, in the rxtx2comm library you have a few classes with the same name and interface than the rxtxcomm ones. So you don't have to make any change on your original code, just swap libraries!

It's not complete, but it does the job. 

feel free to use it!
