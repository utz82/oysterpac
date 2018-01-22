oysterpac
=========

A tool that packs raw binaries into Texas Instruments' graphing calculator executables. The code might be cringeworthy, but unlike certain other TI packers, it actually works even for legacy platforms. The following platforms and formats are supported:

- TI-82/82 Parcus with CrASH shell (.82p)
- TI-83 and compatibles with Ion shell (.83p)
- TI-83 Plus/84 Plus and compatibles (.8xp)

Only machine code programs are supported. Invocation is as follows:

`$ oysterpac <infile> <outfile> [<on-calc filename>]`

