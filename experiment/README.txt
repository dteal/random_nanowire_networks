This folder contains simple nanowire network measurements.

Two PVP@Ag networks, "NW1" and "NW2", were created by the usual method (i.e., nanowire creation followed by dropping NWs in ethanol on electrodes). Multiple small drops were made to (hopefully) distribute the nanowires more evenly. Pictures of the network may be found in ../pictures/dteal_pvp.

Each network has 18 electrodes paired into 9 'inputs' and 9 'outputs'. The inputs and outputs are each numbered 1-9 such that input 1 is closest to output 1, etc.

A number of experiments were run on the two networks. A constant voltage was placed between one input and the corresponding output; the output current was measured over time via a Keithley SCS 4200 system.

Records of the experimental parameters are kept in 'experiment_log.pdf'. The experimental data are kept in 'data/'. 'summary/' contains a subset of the same data collated into representative sets for analysis and plotting.

'theory_calculations.pdf' is unrelated. It contains notes on the basic junction memristance differential equation. Although the equation is difficult to solve exactly as-is, if either the current filament formation or filament decay is neglected, the remaining component produces a simple curve. Thus, all junction behavior can be understood as a combination of these two curves.