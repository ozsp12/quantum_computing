# Quantum-computing references

Last reviewed: 3 August 2026.

## Scope

This bibliography supports the actual contents of the repository: mathematical foundations, circuit-model computation, canonical algorithms, error correction, noisy devices, Qiskit, and Bayesian graphical models. Priority is given to standard monographs, foundational papers, peer-reviewed reviews, and primary project documentation.

## Standard books and lecture notes

1. M. A. Nielsen and I. L. Chuang, *Quantum Computation and Quantum Information*, 10th Anniversary ed. (Cambridge University Press, 2010). [DOI](https://doi.org/10.1017/CBO9780511976667)
2. J. Watrous, *The Theory of Quantum Information* (Cambridge University Press, 2018). [Author’s page](https://cs.uwaterloo.ca/~watrous/TQI/)
3. M. M. Wilde, *Quantum Information Theory*, 2nd ed. (Cambridge University Press, 2017). [DOI](https://doi.org/10.1017/9781316809976) · [arXiv:1106.1445](https://arxiv.org/abs/1106.1445)
4. N. D. Mermin, *Quantum Computer Science: An Introduction* (Cambridge University Press, 2007). [DOI](https://doi.org/10.1017/CBO9780511813870)
5. A. Yu. Kitaev, A. H. Shen, and M. N. Vyalyi, *Classical and Quantum Computation* (American Mathematical Society, 2002). [DOI](https://doi.org/10.1090/gsm/047)
6. P. Kaye, R. Laflamme, and M. Mosca, *An Introduction to Quantum Computing* (Oxford University Press, 2007). [DOI](https://doi.org/10.1093/oso/9780198570004.001.0001)
7. E. Rieffel and W. Polak, *Quantum Computing: A Gentle Introduction* (MIT Press, 2011). [Publisher](https://mitpress.mit.edu/9780262526678/quantum-computing/)
8. C. P. Williams, *Explorations in Quantum Computing*, 2nd ed. (Springer, 2011). [DOI](https://doi.org/10.1007/978-1-84628-887-6)
9. G. K. Brennen, E. Giacobino, and P. K. Lam, eds., *Lecture Notes on Quantum Computing* (2023). [arXiv:2311.08445](https://arxiv.org/abs/2311.08445)
10. J. Preskill, *Lecture Notes for Physics 229: Quantum Information and Computation*. [Caltech](https://theory.caltech.edu/~preskill/ph229/)

## Foundations of quantum computation

11. R. P. Feynman, “Simulating physics with computers,” *Int. J. Theor. Phys.* **21**, 467–488 (1982). [DOI](https://doi.org/10.1007/BF02650179)
12. D. Deutsch, “Quantum theory, the Church–Turing principle and the universal quantum computer,” *Proc. R. Soc. Lond. A* **400**, 97–117 (1985). [DOI](https://doi.org/10.1098/rspa.1985.0070)
13. D. Deutsch and R. Jozsa, “Rapid solution of problems by quantum computation,” *Proc. R. Soc. Lond. A* **439**, 553–558 (1992). [DOI](https://doi.org/10.1098/rspa.1992.0167)
14. E. Bernstein and U. Vazirani, “Quantum complexity theory,” *SIAM J. Comput.* **26**, 1411–1473 (1997). [DOI](https://doi.org/10.1137/S0097539796300921)

## Canonical algorithms and protocols

15. P. W. Shor, “Polynomial-time algorithms for prime factorization and discrete logarithms on a quantum computer,” *SIAM J. Comput.* **26**, 1484–1509 (1997). [DOI](https://doi.org/10.1137/S0097539795293172)
16. L. K. Grover, “A fast quantum mechanical algorithm for database search,” in *STOC ’96*, pp. 212–219 (1996). [DOI](https://doi.org/10.1145/237814.237866) · [arXiv:quant-ph/9605043](https://arxiv.org/abs/quant-ph/9605043)
17. D. R. Simon, “On the power of quantum computation,” *SIAM J. Comput.* **26**, 1474–1483 (1997). [DOI](https://doi.org/10.1137/S0097539796298637)
18. C. H. Bennett et al., “Teleporting an unknown quantum state via dual classical and Einstein–Podolsky–Rosen channels,” *Phys. Rev. Lett.* **70**, 1895–1899 (1993). [DOI](https://doi.org/10.1103/PhysRevLett.70.1895)
19. C. H. Bennett and G. Brassard, “Quantum cryptography: public key distribution and coin tossing,” in *Proceedings of IEEE ICCSSP* (1984). [Reprint DOI](https://doi.org/10.1016/j.tcs.2014.05.025)
20. A. K. Ekert, “Quantum cryptography based on Bell’s theorem,” *Phys. Rev. Lett.* **67**, 661–663 (1991). [DOI](https://doi.org/10.1103/PhysRevLett.67.661)

## Quantum error correction and fault tolerance

21. P. W. Shor, “Scheme for reducing decoherence in quantum computer memory,” *Phys. Rev. A* **52**, R2493–R2496 (1995). [DOI](https://doi.org/10.1103/PhysRevA.52.R2493)
22. A. M. Steane, “Error correcting quantum codes,” *Phys. Rev. Lett.* **77**, 793–797 (1996). [DOI](https://doi.org/10.1103/PhysRevLett.77.793)
23. D. Gottesman, *Stabilizer Codes and Quantum Error Correction*, PhD thesis, Caltech (1997). [arXiv:quant-ph/9705052](https://arxiv.org/abs/quant-ph/9705052)
24. E. Knill and R. Laflamme, “Theory of quantum error-correcting codes,” *Phys. Rev. A* **55**, 900–911 (1997). [DOI](https://doi.org/10.1103/PhysRevA.55.900)
25. D. Aharonov and M. Ben-Or, “Fault-tolerant quantum computation with constant error rate,” *SIAM J. Comput.* **38**, 1207–1282 (2008). [DOI](https://doi.org/10.1137/S0097539799359385)
26. A. G. Fowler et al., “Surface codes: towards practical large-scale quantum computation,” *Phys. Rev. A* **86**, 032324 (2012). [DOI](https://doi.org/10.1103/PhysRevA.86.032324) · [arXiv:1208.0928](https://arxiv.org/abs/1208.0928)

## Variational algorithms and the NISQ regime

27. A. Peruzzo et al., “A variational eigenvalue solver on a photonic quantum processor,” *Nat. Commun.* **5**, 4213 (2014). [DOI](https://doi.org/10.1038/ncomms5213)
28. E. Farhi, J. Goldstone, and S. Gutmann, “A quantum approximate optimization algorithm” (2014). [arXiv:1411.4028](https://arxiv.org/abs/1411.4028)
29. J. Preskill, “Quantum computing in the NISQ era and beyond,” *Quantum* **2**, 79 (2018). [DOI](https://doi.org/10.22331/q-2018-08-06-79)
30. M. Cerezo et al., “Variational quantum algorithms,” *Nat. Rev. Phys.* **3**, 625–644 (2021). [DOI](https://doi.org/10.1038/s42254-021-00348-9)
31. K. Bharti et al., “Noisy intermediate-scale quantum algorithms,” *Rev. Mod. Phys.* **94**, 015004 (2022). [DOI](https://doi.org/10.1103/RevModPhys.94.015004)

## Quantum and classical Bayesian networks

32. M. S. Leifer and D. Poulin, “Quantum graphical models and belief propagation,” *Ann. Phys.* **323**, 1899–1946 (2008). [DOI](https://doi.org/10.1016/j.aop.2007.10.001) · [arXiv:0708.1337](https://arxiv.org/abs/0708.1337)
33. R. R. Tucci, “Quantum Bayesian nets,” *Int. J. Mod. Phys. B* **9**, 295–337 (1995). [arXiv:quant-ph/9706039](https://arxiv.org/abs/quant-ph/9706039)
34. D. Koller and N. Friedman, *Probabilistic Graphical Models: Principles and Techniques* (MIT Press, 2009). [Publisher](https://mitpress.mit.edu/9780262013192/probabilistic-graphical-models/)

## Qiskit and software

35. Qiskit contributors, “Qiskit: an open-source framework for quantum computing” (2021). [DOI](https://doi.org/10.5281/zenodo.2573505) · [Documentation](https://quantum.cloud.ibm.com/docs)
36. R. LaRose, “Overview and comparison of gate-level quantum software platforms,” *Quantum* **3**, 130 (2019). [DOI](https://doi.org/10.22331/q-2019-03-25-130)

## Courses and supplementary material

- [MIT OpenCourseWare 18.435J: Quantum Computation](https://ocw.mit.edu/courses/18-435j-quantum-computation-fall-2003/)
- [IMPA: Introduction to Quantum Computing](https://impa.br/ensino/programas-de-formacao/doutorado/minicursos/introduction-to-quantum-computing/)
- [Classiq Library](https://github.com/Classiq/classiq-library)

## Selection note

The PDF on PbX quantum-dot luminescence retained in `references/` concerns quantum materials rather than quantum computation. It is not included in the canonical computing bibliography. Likewise, a tutorial on modeling classical logic gates is supplementary programming material, not a foundational quantum-computing reference.
