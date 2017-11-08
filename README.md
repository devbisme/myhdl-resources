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
The go-to document for the MyHDL language.

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
low-cost iCEstick FPGA board.

- [MyHDL Cheat Sheet](https://bitbucket.org/nico-dev/myhdl_cheat_sheet/src) -
An abstract for the MyHDL language keywords.

- [modbv Example](https://bitbucket.org/cfelton/examples/src/tip/rrs_modbv/) - 
An example of the use of the modbv type introduced in MyHDL 0.8.

- [LED Strober](https://www.fpgarelated.com/showarticle/25.php) - 
Shows a complete implementation of a circuit that recreates
the strobe effect of the Knightrider Trans Am.

- [Audio Echo](https://www.fpgarelated.com/showarticle/34.php) -
Describes how to produce an echo on a stream of digitized audio samples.
A [companion article](https://www.fpgarelated.com/showarticle/41.php) adds further details
concerning the actual implementation with an AIC23 codec chip.

- [Simple Co-Simulation Example](https://gist.github.com/j-marjanovic/1cd36b9da44280e890b6) -
This code snippet uses three modules to present the absolute minimum for a
co-simulation of Verilog code and MyHDL code.

- [OO Design in MyHDL](https://gist.github.com/josyb/2e43c9ad7ffa772d52dfd66cb660dc4a) -
An example of using object-oriented design principles with MyHDL.


## Projects

- [Johnson Counter](http://myhdl.org/docs/examples/jc2.html) -
Presents the design of a reversible, glitch-free, 4 bit Johnson counter.

- [Stopwatch](http://myhdl.org/docs/examples/stopwatch/) -
Describes the design of a simple stopwatch.

- [Pulse Width Modlator](https://bitbucket.org/cfelton/examples/src/tip/pwm?at=default) -
A simple PWM along with several test setups.

- [Cordic-Based Sine Computer](http://myhdl.org/docs/examples/sinecomp/) -
Presents the design of a sine and cosine computer.

- [Hardware Sorters](https://github.com/xesscorp/Hardware-Sorters) -
A [Jupyter](jupyter.org) notebook describing, simulating, and comparing 
two hardware-based circuits for sorting a list of numbers.

- [Exploring Random Number Generators with MyHDL](https://github.com/xesscorp/CAT-Board/blob/master/tests/RNG_with_MyHDL.ipynb) -
Illustrates the advantages of using MyHDL and Python in designing and testing a random number generator (RNG).

- [Simple IIR Filter](https://bitbucket.org/cfelton/examples/src/tip/siir/) -
A simple infinite impulse response (IIR) Lowpass Direct Form I Filter.

- [Simple FIR Filter](https://bitbucket.org/cfelton/examples/src/tip/firfilt?at=default) -
A simple finite impulse response (FIR) filter.

- [Recursive FFT](https://bitbucket.org/cfelton/examples/src/tip/rfft/) -
Fast Fourier Transform in MyHDL and translatable to Verilog or VHDL for hardware implementation.
See [this](https://www.dsprelated.com/showcode/16.php) for additional explanation.

- [AIC23b Audio Codec Interface](https://bitbucket.org/cfelton/examples/src/tip/mycores/aic23?at=default) -
An interface for configuring the [AIC23 codec](http://www.ti.com/product/TLV320AIC23B) and sampling/generating audio signals.

- [myhdl_lib](https://github.com/nkavaldj/myhdl_lib) -
A MyHDL library of generic design components, e.g. memory, fifo, multiplexor, de-multiplexor, arbiter, etc. All components are tested with Icarus Verilog simulator.

- [rhea](https://github.com/cfelton/rhea) -
A collection of HDL cores along with a small set of utilities to augment the MyHDL types and functions as well as FPGA build automation tools.

- [KalmanFilter](https://github.com/josyb/KalmanFilter) - 
A simple, low-resource usage Kalman Filter using shared resources.

- [myhdl_simple_uart](https://github.com/andrecp/myhdl_simple_uart) - 
Implements a simple UART in MyHDL and generates the VHDL files. It has been tested in a DE2-115 board.

- [Spiking Neuron](https://github.com/CodeReclaimers/myhdl-experiments/blob/master/izhikevitch/neuron.py) -
Implements a spiking neuron based on the model described in
Izhikevich, E. M., "Simple Model of Spiking Neurons"
IEEE TRANSACTIONS ON NEURAL NETWORKS, VOL. 14, NO. 6, NOVEMBER 2003.

- [Algol RISCV CPU core](https://github.com/AngelTerrones/Algol) -
A CPU core that implements the RISC-V RV32IM Instruction Set.

- [alt.hdl](https://github.com/cfelton/alt.hdl) -
A collection of complete and partial design examples built using MyHDL, bsv, and chisel.

- [PyMIPS](https://github.com/mgaitan/pymips) -
A formal implementation of a MIPS processor as described in *Computer Organization and Design* by Hennessy/Patterson.

- [RISC-V](https://github.com/jck/riscv) -
A RISC-V implementation and tools.

- [MyBlaze](https://github.com/wware/myblaze) -
a synthesizable clone of the MicroBlaze Soft Processor.


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

- [Synthia](https://github.com/nturley/synthia) -
A simple IDE that uses MyHDL, yosys, and arachne-pnr to target the ICEStick.

- [pyFDA](https://github.com/chipmuenk/pyFDA) -
A GUI-based tool for analysing and designing discrete time filters.
May be using MyHDL to generate HDL implementations of the filters.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [XESS Corp.](http://xess.com) has waived all copyright and related or neighboring rights to this work.
