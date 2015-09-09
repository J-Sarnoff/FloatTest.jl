# FloatTest.jl
###### Jeffrey Sarnoff on 2015-Sep-09 at 04:21:07 UTC in USA(NY)
##### tests: no double rounding, rounds without extra precison, chip/software fma works

Just copy the raw file and paste it into your REPL

There are only three tests, and they take much less time than does pasting.

If they pass you will see

*The numerics tested work properly.*

If any test does not pass, that information is shown.  
And it would be generally useful to know the test that failed and versioninfo().

I want to avoid relying on capabilities that are not very widely shared.


```
Julia Version 0.4.0-pre+7380
Commit 6ef451c (2015-09-08 04:13 UTC)
Platform Info:
  System: Linux (x86_64-unknown-linux-gnu)
  CPU: Intel(R) Core(TM) i7-4960X CPU @ 3.60GHz
  WORD_SIZE: 64
```



