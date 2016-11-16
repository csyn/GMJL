# GNU Make Standard Library

This is a version of GMSL modified to be capable of arbitrary signed arithmetic.

Visit http://gmsl.sf.net for more details

To use the GMSL in your Makefile make sure that you have the files

```
gmsl
__gmsl
```

Add

`include gmsl`

to your Makefile(s).

To run the GMSL test suite have

```
gmsl
__gmsl
gmsl-tests
```

And then run

`make test`
