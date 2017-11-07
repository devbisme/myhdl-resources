# MyHDL Resources

> A curated list of tutorials, projects, and third-party tools to be used in conjunction with the
open source [MyHDL](http://myhdl.org/) hardware design language.

*You can add your own stuff to this! Please read the [contribution guidelines](contributing.md) to see how.*



## Table of Contents

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Tutorials](#tutorials)
- [Projects](#projects)
- [Third-party Tools](#third-party-tools)

<!-- /TOC -->


## Tutorials

- [MyHDL Reference Manual](http://docs.myhdl.org/en/stable/) -
The go-to place for the MyHDL language.

- [Hello World](http://myhdl.org/docs/examples/helloworld.html) -
Shows how a demonstrator design that was originally coded in VHDL can be done in MyHDL.

- [Flip-Flops and Latches](http://myhdl.org/docs/examples/flipflops.html) -
Explains basic MyHDL usage with small, widely-known circuits.

- [Bitonic Sort](http://myhdl.org/docs/examples/bitonic/) -
Presents possibilities for describing hardware structures in MyHDL, focusing on
a classic sorting function.

- [PygMyHDL Tutorials](https://github.com/xesscorp/pygmyhdl#getting-started) -
A sequence of Jupyter notebooks that use PygMyHDL (MyHDL + simple wrapper)
to describe, compile, download and run several digital logic circuits on the
low-cost iCEstick FPGA


## Projects

- [Johnson Counter](http://myhdl.org/docs/examples/jc2.html) -
Presents the design of a reversible, glitch-free, 4 bit Johnson counter.

- [Stopwatch](http://myhdl.org/docs/examples/stopwatch/) -
Describes the design of a simple stopwatch.

- [Cordic-Based Sine Computer](http://myhdl.org/docs/examples/sinecomp/) -
Presents the design of a sine and cosine computer.

- [Hardware Sorters](https://github.com/xesscorp/Hardware-Sorters) -
A [Jupyter](jupyter.org) notebook describing, simulating, and comparing 
two hardware-based circuits for sorting a list of numbers.

- [Exploring Random Number Generators with MyHDL](https://github.com/xesscorp/CAT-Board/blob/master/tests/RNG_with_MyHDL.ipynb) -
Illustrates the advantages of using MyHDL and Python in designing and testing a random number generator (RNG). 


## Third-Party Tools

- [myhdlpeek](https://github.com/xesscorp/myhdlpeek) - 
A Python package that lets you monitor and display signal waveforms from your MyHDL digital design in a Jupyter notebook.

- [PygMyHDL](https://github.com/xesscorp/pygmyhdl) - 
A Python package that places a thin-wrapper around MyHDL to make it a bit easier for
beginners to get started.

- [Ovenbird](https://github.com/hgomersall/Ovenbird) - 
A tool for merging the MyHDL workflow with Vivado.

- [MyHDLXilinxUnisimLib](https://bitbucket.org/nico-dev/myhdl_xilinx_unisim_lib/) - 
MyHldXilinxUnisimLib lets you use Xilinx Unisim components within a MyHDL project.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [XESS Corp.](http://xess.com) has waived all copyright and related or neighboring rights to this work.
