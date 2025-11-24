# Final Year Project Thesis: Finite Element Solver for Light Scattering

This repository contains the LaTeX source code and documentation for my Final Year Project (FYP) thesis submitted to the Faculty of Engineering, Universiti Malaya.

**Author:** Lee Shien Wei  
**Degree:** Bachelor of Engineering (Hons) Mechanical Engineering  
**Target Submission:** 2026  

## 📖 Project Overview

The primary objective of this project is the **Development of a Finite Element Solver for Light Scattering Simulation**. 
This thesis documents the mathematical formulation (Maxwell's equations, Helmholtz equation), numerical implementation using **FEniCSx** and validation of the solver.

## 📂 Repository Structure

The LaTeX project is structured efficiently to handle a large document using the `\include` system:
```text
.
├── main_report.tex       # The master file (compiles everything)
├── references.bib        # Bibliography database (BibTeX)
├── .gitignore            # Git configuration for LaTeX temp files
├── chapters/             # Individual chapters (Intro, Math Formulation, etc.)
├── frontmatter/          # Abstract, Acknowledgement, Declaration
└── images/               # Figures and simulation results
