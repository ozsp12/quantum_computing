# Quantum Computing

Educational and research notebooks on classical logic, linear algebra, quantum circuits, Qiskit simulation, quantum error correction, and Bayesian networks.

The original notebooks are preserved exactly under `codes_obsolete/`. Reviewed notebooks under `codes/` use English Markdown, comments, labels, and filenames. Their historical outputs were cleared so that displayed results cannot be confused with a fresh execution.

## Repository structure

| Path | Contents |
| --- | --- |
| [`codes/`](codes/) | Reviewed English notebooks organized by subject. |
| [`codes_obsolete/`](codes_obsolete/) | Exact archival copies of every original notebook. |
| [`docs/CODE_REVIEW.md`](docs/CODE_REVIEW.md) | File-by-file technical inspection and limitations. |
| [`references/`](references/) | Reference files retained from the original repository. |
| [`REFERENCES.md`](REFERENCES.md) | Canonical books, foundational papers, reviews, and primary software references. |

## Contents

- **Classical computing:** Boolean logic, truth tables, and classical gates.
- **Linear algebra:** vectors, matrices, tensor products, inner products, polarization states, and Bloch-sphere representations.
- **Quantum circuits:** Pauli, Hadamard, rotation, and controlled-NOT gates; statevectors; measurement; and finite-shot simulation.
- **Quantum error correction:** repetition-code examples, Shor-code experiments, stabilizers, syndrome extraction, transversal gates, and injected Pauli errors.
- **Probabilistic models:** classical Bayesian-network construction and inference. The corresponding notebook is not a quantum Bayesian-network implementation; the distinction is documented explicitly.

## Installation

Create a dedicated Python environment and install the packages required by the notebook you intend to run. The principal dependencies are:

```bash
python -m pip install numpy pandas matplotlib qiskit qiskit-aer pgmpy networkx schemdraw pyzx
```

Qiskit APIs change over time. The reviewed notebooks preserve the original computational logic and should be tested against a pinned environment before being used as reproducible research artifacts.

## Execution and validation

Open the notebooks in JupyterLab and execute cells sequentially. Statevector calculations must occur before measurement unless the notebook intentionally models measurement. Qiskit displays multi-qubit basis states using little-endian register conventions; always state the adopted ket ordering when comparing circuit diagrams, statevectors, and matrices.

All reviewed and archived notebooks were validated as notebook JSON. This structural validation does not certify the mathematical correctness of every circuit or error-correction claim. See [`docs/CODE_REVIEW.md`](docs/CODE_REVIEW.md).

## References

The curated bibliography in [`REFERENCES.md`](REFERENCES.md) starts with standard texts by Nielsen and Chuang, Watrous, Wilde, Mermin, and Kitaev–Shen–Vyalyi, then covers foundational algorithms, error correction, NISQ methods, quantum Bayesian networks, and Qiskit.

## Author

**Dr. Osvaldo L. Santos-Pereira** — [Academic webpage](https://ozsp12.github.io/) · [Lattes](http://lattes.cnpq.br/6730251976463283) · [ORCID](https://orcid.org/0000-0003-2231-517X) · [Google Scholar](https://scholar.google.com/citations?user=HIZp0X8AAAAJ&hl=en) · [ResearchGate](https://www.researchgate.net/profile/Osvaldo-Santos-Pereira) · [GitHub](https://github.com/ozsp12) · [LinkedIn](https://www.linkedin.com/in/ozsp12) · [Substack](https://substack.com/@olsp1982) · [Medium](https://medium.com/@ozsp12) · [YouTube](https://www.youtube.com/@ozlsp12) · [X](https://x.com/ozsp12)

## License

No explicit repository-wide license is currently provided. The included books, articles, and generated PDFs remain subject to their respective copyright and publisher terms.
