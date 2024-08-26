 The 6 alternative experiments have been done for expectation value of weight 1 Z observables for 7 qubit GHZ state. Ideal outcome is 0.  We compared all 6 experiments.
Conclusions: 1. Qubit Reuse +cut + unrolled approach is not giving benefit over  pre-existing approaches. 
2.For the experiment: "Run the uncut qubit-reset version of GHZ and get noisy expval",  Estimator did not give error even if it gets "3 qubit circuit"  and "7 qubit observable". However, it gave the worst answer because of re- ordering of qubits.
3. Clever Circuit Cutting is beneficial compared to run the circuit on single QPU.

Note: mapomatic is not used because The same algorithm used in mapomatic is integrated into the Qiskit transpiler by default as the VF2PostLayout pass which gets run by default in optimization levels 1, 2, and 3.
