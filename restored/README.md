This is a version of ICAL formatted and modifed to run under SPITBOLx64(https://github.com/spitbol/x64). You can invoke the compiler thusly:

```
spitbol ical.sbl < test.ical 
```

ICAL produces multiple output files. The one that contains the final program is called `SCRATCH`.

There are some oddities about this version of INTERCAL compared to later versions. First of all, you can't compile a single line program. You will need at least 3 lines of code, with one `PLEASE` statement among them.

Some statements are in a dubous state. Detection of READ OUT, ABSTAIN, and FORGET isn't working correctly right now. I reccomend any willing programmer take a look at corecting those issues.