# Koopman Control via Nyström Kernel Approximation (Beamer Presentation)

This repository contains the LaTeX Beamer source code for my academic presentation:

**Koopman Control via Nyström Kernel Approximation**
*Muthana Alsaadi — College of Information Engineering, University of Al-Nahrain*
September 2025

The slides are based on the paper:
[Edoardo Caldarelli et al., *Linear quadratic control of nonlinear systems with Koopman operator learning and the Nyström method*, Automatica, Vol. 177, 2025](https://doi.org/10.1016/j.automatica.2025.112302)

---

## Repository Contents

```
.
├── main.tex          # Main presentation source
├── summary.png       # Kernel + Nyström summary diagram
├── paper_code.png    # QR code for the reference paper
├── repo.png          # QR code linking to this repository
├── README.md         # Documentation
```

---

## How to Compile

### Local Setup

1. Install a LaTeX distribution:

   * **Windows** → [MiKTeX](https://miktex.org/download)
   * **macOS** → [MacTeX](https://tug.org/mactex/)
   * **Linux** → `sudo apt install texlive-full`

2. Clone this repository:

   ```bash
   git clone https://github.com/muthanii/Koopman-Control-via-Nystrom-Kernel-Approximation.git
   cd Koopman-Control-via-Nystrom-Kernel-Approximation
   ```

3. Compile with:

   ```bash
   pdflatex main.tex
   ```

   This generates `main.pdf`.

### VS Code + LaTeX Workshop

* Install [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).
* Open the folder in VS Code.
* Build with <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>B</kbd>.

### Overleaf

* Upload the project as a `.zip` and compile online.
  *(Note: Overleaf free accounts have compile limits.)*

---

## Slide Highlights

* **Motivation:** Why controlling nonlinear systems is hard.
* **Koopman Operator:** Lifting dynamics into linear form.
* **Nyström Approximation:** Making infinite-dimensional kernels computable.
* **LQR Formulation:** Applying efficient control.
* **Theoretical Proofs:** Convergence of \$\widetilde{G}\_\gamma\$, \$\widetilde{P}\$, and cost \$J\$.
* **Quizzes & Wrap-Up:** Audience engagement and resources.

---

## References

* Automatica paper: [DOI link](https://doi.org/10.1016/j.automatica.2025.112302)
* Full source: GitHub repository (QR code provided in slides)

---

## License

This material is shared for academic and educational purposes.
You are free to adapt and reuse the Beamer code with attribution.
