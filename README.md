<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.webp">
    <img src="assets/logo-light.webp" width="170" alt="Kooshan Maleki's logo: the bra-ket expression |κ⟩⟨μ|">
  </picture>
</p>

<h1 align="center">Kooshan Maleki</h1>

<p align="center">
  Master's student &amp; researcher<br>
  <sub>KU Leuven · eBRAIN Lab, NYU Abu Dhabi</sub>
</p>

<p align="center">
  <a href="https://kooshan.info"><img src="https://img.shields.io/badge/kooshan.info-1a1b1d?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://scholar.google.com/citations?user=Y-WZ4wkAAAAJ"><img src="https://img.shields.io/badge/Scholar-1a1b1d?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://www.linkedin.com/in/Kooshan-Maleki"><img src="https://img.shields.io/badge/LinkedIn-1a1b1d?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIxLjUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI+PHBhdGggZD0iTTIxIDh2OGE1IDUgMCAwMS01IDVIOGE1IDUgMCAwMS01LTVWOGE1IDUgMCAwMTUtNWg4YTUgNSAwIDAxNSA1ek03IDE3di03Ii8+PHBhdGggZD0iTTExIDE3di0zLjI1TTExIDEwdjMuNzVtMCAwYzAtMy43NSA2LTMuNzUgNiAwVjE3TTcgNy4wMWwuMDEtLjAxMSIvPjwvc3ZnPg==" alt="LinkedIn"></a>
  <a href="https://x.com/Kooshano"><img src="https://img.shields.io/badge/X-1a1b1d?style=flat-square&logo=x&logoColor=white" alt="X"></a>
  <a href="mailto:Kooshan.m@nyu.edu"><img src="https://img.shields.io/badge/Email-1a1b1d?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### Hello 👋,

I'm a Master of Engineering: Computer Science student at **KU Leuven** and a researcher at the
**eBRAIN Lab, NYU Abu Dhabi**. I work on hybrid quantum-classical machine learning: the part of
quantum computing where the interesting question is not whether a circuit runs, but whether it
earns its place next to a classical model.

Usually it doesn't. Working out which cases are the exception, and why, is the job.

```
        ┌───┐                 ┌─┐
 |0⟩ ───┤ H ├────────●────────┤M├───
        └───┘        │        └╥┘
        ┌───┐   ┌────┴────┐    ║
 |0⟩ ───┤ H ├───┤ RY(θ)   ├────╫────
        └───┘   └─────────┘    ║
                               ║
   NSGA-II ◄───────────────────╝
   accuracy · circuit cost · partitionability
```

---

### Publications

**QNAS: A Neural Architecture Search Framework for Accurate and Efficient Quantum Neural Networks**
<br><sub>K. Maleki, A. Marchisio, M. Shafique · IEEE IJCNN 2026 (WCCI 2026), Maastricht</sub>

Multi-objective search over hybrid quantum-classical architectures. NSGA-II optimises accuracy,
circuit cost and wire-cutting partitionability at once, instead of chasing accuracy and discovering
later that the circuit will not fit on anything real.

<a href="https://arxiv.org/abs/2604.07013"><img src="https://img.shields.io/badge/arXiv-2604.07013-1a1b1d?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv"></a>
<a href="https://github.com/Kooshano/QNAS"><img src="https://img.shields.io/badge/Code-1a1b1d?style=flat-square&logo=github&logoColor=white" alt="Code"></a>

---

### Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Kooshano/QNAS">QNAS</a></h4>
      <p><strong>Quantum neural architecture search</strong></p>
      <p>Multi-objective NAS for hybrid quantum-classical networks, with Pareto-front analysis and
      checkpoint-based early stopping so the hopeless candidates stop burning simulator time.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-6b6e73?style=flat-square&logo=python&logoColor=white">
        <img src="https://img.shields.io/badge/PennyLane-6b6e73?style=flat-square&logoColor=white">
        <img src="https://img.shields.io/badge/PyTorch-6b6e73?style=flat-square&logo=pytorch&logoColor=white">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>Pauli <sub>(coming soon)</sub></h4>
      <p><strong>Multi-scale Pauli CNN</strong></p>
      <p>Pauli decomposition by deep learning with physics-informed constraints. A multi-scale CNN
      aligned to the tensor-product structure, benchmarked against the analytical methods it hopes
      to beat.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-6b6e73?style=flat-square&logo=python&logoColor=white">
        <img src="https://img.shields.io/badge/PyTorch-6b6e73?style=flat-square&logo=pytorch&logoColor=white">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Kooshano/HHL">HHL</a></h4>
      <p><strong>Quantum linear solver</strong></p>
      <p>End-to-end HHL pipeline with GPU-aware workflows, and the classical baselines that keep it
      honest. My bachelor thesis, in code form.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-6b6e73?style=flat-square&logo=python&logoColor=white">
        <img src="https://img.shields.io/badge/Qiskit-6b6e73?style=flat-square&logo=qiskit&logoColor=white">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Kooshano/KAN">KAN</a></h4>
      <p><strong>Kolmogorov-Arnold networks</strong></p>
      <p>A from-scratch KAN with custom activations and hand-written backpropagation, built mostly
      to find out whether the hype survived contact with a debugger.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-6b6e73?style=flat-square&logo=python&logoColor=white">
        <img src="https://img.shields.io/badge/Jupyter-6b6e73?style=flat-square&logo=jupyter&logoColor=white">
      </p>
    </td>
  </tr>
</table>

---

<p align="center">
  <sub>Open to collaboration on quantum machine learning, QNN optimisation and hybrid algorithm design.</sub><br>
  <sub><a href="mailto:Kooshan.m@nyu.edu">Kooshan.m@nyu.edu</a> · <a href="https://kooshan.info">kooshan.info</a> · Leuven, Belgium</sub>
</p>
