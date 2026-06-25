# 🌊 Welcome Back

Scriber Labs develops educational and research-oriented computational models for exploring how structure and dynmaics can be recovered from data.

---
### 🔖 Core Philosophical Commitments
1. Interpretiblity
2. Clarity (physics first, data second)
3. Parsimony
4. Scalability
5. Computationally efficient
6. Practicality (optional for low-fidelity projects and apps/widgets)
    - scientific value
    - educational
7. Sing-develepor feasibility



---

## 🪀 Project 1: [`lf-pinn-harmonic-oscillator`](https://github.com/Scriber-Labs/lf-pinn-harmonic-oscillator)
### 🏡 Take-Home Messages:
> Physics residual minimization does got guarantee physical inveriants unless sampling resolves the solution spectrum. This is a manifestation of **spectral bias**.

> Residual minimization approximates the operator constraint, but conservation emerges from the generator s tructure. If the generator isnt structurally preserved (via sampling or architecture), invariants drift even under converged optimization.
> - This connects spectral bias in neural nets to...
>    - Nyquist sampling theory
>    - Hamiltonian structure
>    - Conservation Laws
>    - PINN failure modes



---
## References
```tex
@article{basir2022pinnfailures,
  author    = {Basir, Soroush and Senocak, Inanc},
  title     = {Critical Investigation of Failure Modes in Physics-Informed Neural Networks},
  booktitle = {AIAA SCITECH 2022 Forum},
  year      = {2022},
  doi       = {10.2514/6.2022-2353}
}

@book{brunton2022datadriven,
  author    = {Brunton, Steven L. and Kutz, J. Nathan},
  title     = {Data-Driven Science and Engineering: Machine Learning, Dynamical Systems, and Control},
  publisher = {Cambridge University Press},
  year      = {2022},
  edition   = {2}
}

@incollection{hestenes1993hamiltonian,
  author    = {Hestenes, David},
  title     = {Hamiltonian Mechanics with Geometric Calculus},
  booktitle = {Clifford Algebras and Their Applications in Mathematical Physics},
  pages     = {203--214},
  publisher = {Springer},
  year      = {1993},
  doi       = {10.1007/978-94-011-1719-7_25}
}

@article{kutzbrunton2022parsimony,
  author  = {Kutz, J. Nathan and Brunton, Steven L.},
  title   = {Parsimony as the ultimate regularizer for physics-informed machine learning},
  journal = {Nonlinear Dynamics},
  volume  = {107},
  number  = {3},
  pages   = {1801--1817},
  year    = {2022},
  doi     = {10.1007/s11071-021-07118-3}
}

@article{raissi2019pinns,
  author  = {Raissi, Maziar and Perdikaris, Paris and Karniadakis, George Em},
  title   = {Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations},
  journal = {Journal of Computational Physics},
  volume  = {378},
  pages   = {686--707},
  year    = {2019},
  doi     = {10.1016/j.jcp.2018.10.045}
}

```
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
