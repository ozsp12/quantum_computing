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

**Dr. Osvaldo L. Santos-Pereira**

<a href="mailto:olsp@if.ufrj.br"><img src="https://api.iconify.design/mdi:email.svg?color=%23888888" height="22" alt="Email" align="absmiddle"></a> **Email:** [olsp@if.ufrj.br](mailto:olsp@if.ufrj.br)  
<a href="https://ozsp12.github.io/"><img src="https://api.iconify.design/mdi:web.svg?color=%23888888" height="22" alt="Academic webpage" align="absmiddle"></a> **Academic webpage:** [https://ozsp12.github.io/](https://ozsp12.github.io/)  
<a href="http://lattes.cnpq.br/6730251976463283"><img src="https://api.iconify.design/mdi:account-school.svg?color=%23888888" height="22" alt="Lattes" align="absmiddle"></a> **Lattes:** [http://lattes.cnpq.br/6730251976463283](http://lattes.cnpq.br/6730251976463283)  
<a href="https://orcid.org/0000-0003-2231-517X"><img src="https://cdn.simpleicons.org/orcid/A6CE39" height="22" alt="ORCID" align="absmiddle"></a> **ORCID:** [https://orcid.org/0000-0003-2231-517X](https://orcid.org/0000-0003-2231-517X)  
<a href="https://scholar.google.com/citations?user=HIZp0X8AAAAJ&amp;hl=en"><img src="https://cdn.simpleicons.org/googlescholar/4285F4" height="22" alt="Google Scholar" align="absmiddle"></a> **Google Scholar:** [https://scholar.google.com/citations?user=HIZp0X8AAAAJ&hl=en](https://scholar.google.com/citations?user=HIZp0X8AAAAJ&hl=en)  
<a href="https://www.researchgate.net/profile/Osvaldo-Santos-Pereira"><img src="https://cdn.simpleicons.org/researchgate/00CCBB" height="22" alt="ResearchGate" align="absmiddle"></a> **ResearchGate:** [https://www.researchgate.net/profile/Osvaldo-Santos-Pereira](https://www.researchgate.net/profile/Osvaldo-Santos-Pereira)  
<a href="https://github.com/ozsp12"><img src="https://cdn.simpleicons.org/github/888888" height="22" alt="GitHub" align="absmiddle"></a> **GitHub:** [https://github.com/ozsp12](https://github.com/ozsp12)  
<a href="https://br.linkedin.com/in/ozsp12"><img src="https://api.iconify.design/mdi:linkedin.svg?color=%230A66C2" height="22" alt="LinkedIn" align="absmiddle"></a> **LinkedIn:** [https://br.linkedin.com/in/ozsp12](https://br.linkedin.com/in/ozsp12)  
<a href="https://substack.com/@olsp1982"><img src="https://cdn.simpleicons.org/substack/FF6719" height="22" alt="Substack" align="absmiddle"></a> **Substack:** [https://substack.com/@olsp1982](https://substack.com/@olsp1982)  
<a href="https://medium.com/@ozsp12"><img src="https://cdn.simpleicons.org/medium/888888" height="22" alt="Medium" align="absmiddle"></a> **Medium:** [https://medium.com/@ozsp12](https://medium.com/@ozsp12)  
<a href="https://www.youtube.com/@ozlsp12"><img src="https://cdn.simpleicons.org/youtube/FF0000" height="22" alt="YouTube" align="absmiddle"></a> **YouTube:** [https://www.youtube.com/@ozlsp12](https://www.youtube.com/@ozlsp12)  
<a href="https://x.com/ozsp12"><img src="https://cdn.simpleicons.org/x/888888" height="22" alt="X" align="absmiddle"></a> **X:** [https://x.com/ozsp12](https://x.com/ozsp12)

## License

No explicit repository-wide license is currently provided. The included books, articles, and generated PDFs remain subject to their respective copyright and publisher terms.
