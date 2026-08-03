# Code inspection

Inspection date: 3 August 2026.

## Scope

The review covered 14 notebooks. Exact originals are stored under `codes_obsolete/`; reviewed English editions are under `codes/`. Every reviewed notebook has English documentation, a purpose comment for executable cells, cleared historical outputs, and provenance metadata.

## Principal findings

- Two copies of `linear_algebra_basics.ipynb` are identical. Both originals were archived; one reviewed copy is marked as a provenance duplicate.
- The extended classical-gates notebook contains many empty cells and repeated exploratory sections. The smaller English notebook is the cleaner entry point.
- The circuit-example notebook is mathematically useful but unusually long for a single example. Qiskit’s little-endian ket convention must be stated consistently when matrices and circuit diagrams are compared.
- Some notebooks import the same Qiskit objects repeatedly. Imports and simulator setup should eventually be centralized.
- Statevector calculations and measurement-based simulations serve different purposes. Once measurement is appended, recovering the preceding pure state requires using an earlier circuit or removing final measurements.
- Finite-shot counts approximate Born probabilities; they are not exact amplitudes.
- The Shor-code notebooks contain exploratory recovery logic. Stabilizer expectation values, syndrome extraction, recovery, decoding, and logical fidelity must be distinguished. A high physical-state fidelity in one constructed case is not a general proof of fault tolerance.
- Transversal gates are code-dependent. A gate being transversal for one encoding does not imply that it is transversal or logically correct for another.
- The file named `quantum_bayesian_network.ipynb` implements a classical discrete Bayesian network with `pgmpy`. It does not define quantum conditional states, density operators, or a quantum Bayesian network in the sense of Tucci or Leifer–Poulin.
- The Pauli-matrix exercise correctly distinguishes (X|+\rangle=|+\rangle), (Z|+\rangle=|-\rangle), Hermiticity, and the phase factor in products of Pauli matrices.

## Validation performed

- All 28 notebooks—14 archived and 14 reviewed—parse as valid notebook JSON.
- Archived notebooks are exact byte copies of their originals.
- Reviewed notebooks retain the original code order, use English narrative material, and contain no stored outputs.
- Root-level and Portuguese-directory notebook files are replaced by the organized archival and reviewed trees.

## Recommended next step

Add a pinned environment file and automated tests for circuit unitary matrices, state normalization, qubit ordering, measurement distributions within statistical tolerance, syndrome tables, recovery maps, and logical fidelities. Software compatibility should be tested against a declared Qiskit release rather than against an unbounded latest version.
