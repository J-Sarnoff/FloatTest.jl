# FloatTest.jl
###### Jeffrey Sarnoff on 2015-Sep-09 at 04:21:07 UTC in USA(NY)
##### tests: no double rounding, rounds without extra precison, chip/software fma works

Just copy the raw file (or the file text) and paste it into your REPL

There are only three tests, and they take much less time than does pasting.

If they pass you will see

_**The numerics tested work properly.**_

If any test does not pass, or the version of Julia in use does not support fma, that information is shown.  It would be generally useful to know the test that failed and versioninfo().

I want to rely on capabilities that are very widely shared.


##### references

The rounding tests come from from
  Sun's Numerical Computation Guide Appendix D
  which is an expansion upon David Goldberg's
  "What Every Computer Scientist Should Know About Floating-Point Arithmetic"
  http://www.validlab.com/goldberg/addendum.html

The fma test is from
  A Look at the Impact of AMD Bulldozer FMA4 Instructions on Data Precision
  by Zhen Wang, PGI Applications Engineer  October 2011
  https://www.pgroup.com/lit/articles/insider/v3n3a4.htm
