# Delimited-Control Operators shift0/dollar:
- **Thesis**: [A Fine-Grained Evaluation Strategy for Delimited-Control Operators shift0/dollar](Thesis.pdf)
- **Contribution**:
  - Formalise `λ$` calculus with its **evaluation** strategy
  - Introduce an **evaluation** strategy for `λc$` (a fine-grained version of `λ$`)
  - Define **similarity** relations to prove **correspondance** between both calculi in a form of **simulations** which state that: *similar terms compute to similar values*
- Files:
  - [`λ$` calculus](LambdaDollar.v) (paper reference: [section 2.2](https://ii.uni.wroc.pl/~dabi/publications/APLAS12/materzok-biernacki-aplas12.pdf))
  - [`λc$` calculus: a Fine-Grained version of `λ$`](LambdaLetDollar.v) (paper reference: [Figure 1](https://dl.acm.org/doi/10.1145/3479394.3479399))
  - Correspondence between `λ$` and `λc$`:
    - [Simulation: `λ$` to `λc$`](LambdaDollarToLet.v)
    - [Simulation: `λc$` to `λ$`](LambdaLetToDollar.v)

Makefile generated by `coq_makefile -f _CoqProject *.v -o Makefile`

---

*This is an archived sub-repository of [lambda-formalizations](https://github.com/Kamirus/lambda-formalizations) that hosts the formalisation code of my thesis.*
