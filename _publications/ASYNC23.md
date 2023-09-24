---
title: "Designing Self-timed Asynchronous Circuits with Chisel"
collection: publications
permalink: /publication/ASYNC-Chisel
excerpt: 'As an embedded library of the Scala programming language that leverages many features of object-oriented and functional programming, Chisel is a new generation hardware construction language designed for agile development. This paper proposes a design flow for designing self-timed asynchronous circuits using Chisel, which has two main features: 1) a reusable asynchronous library is created based on Chisel, which allows designers to develop flexible asynchronous modules for different applications; 2) the analysis of asynchronous circuits designed with Chisel is automatic, including auto-timing constraints generation. In our flow, designers use Chisel and a set of reusable asynchronous libraries to describe the asynchronous circuit. Then, the Chisel compiler generates an intermediate representation. Next, the circuit transformation module analyzes the IR to generate the final Verilog netlist and timing constraint files. Finally, the backend design is realized with commercial EDA tools. To demonstrate the feasibility of our approach, we implement the Fibonacci and greatest common divisor circuits on FPGA and compare them with previous designs with VHDL. We find that Chisel-based designs have at least 70% fewer lines of code. Besides, we design an asynchronous SNN processor(ANP-T) using Chisel and implement it with a 22nm CMOS process to verify our approach in the ASIC flow.'
date: 2023-09-06
venue: 'ASYNC'
paperurl: 'https://ieeexplore.ieee.org/document/10239616'
citation: '**Jilin Zhang**, Chunqi Qian, Ddxuan Huo, Jian Zhang and Hong Chen, "Designing Self-timed Asynchronous Circuits with Chisel," 2023 28th IEEE International Symposium on Asynchronous Circuits and Systems (ASYNC), Beijing, China, 2023, pp. 27-33, doi: 10.1109/ASYNC58294.2023.10239616.'
---
