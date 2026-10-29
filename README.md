# Exact Λ-Vacuum Solutions with Curled Extra Dimensions, 4D to 7D

**Harry S. (Bud) Simrin**

This repository contains exact solutions of Einstein's vacuum field equations with a cosmological constant,

**Rμν = Λ gμν**,

for an expanding universe in 4 to 7 spacetime dimensions. The extra dimensions are curled up into circles, tori, and spheres.

Every case is solved from scratch, one field equation at a time, in a Mathematica notebook that shows each step: setting up the metric, computing the Christoffel symbols and the Ricci tensor, and solving the field equations, with explanations along the way. The aim is to show *how* such solutions are found, including the dead ends, not just the finished results.

## Role of AI in this work

The notebooks are my own work. Each case was reviewed by Claude, an AI assistant made by Anthropic. Claude independently checked the derivations and the final solutions with SymPy (Python) and Mathematica, including substituting each solution back into the field equations and verifying its constraints. It also reviewed the notebook text and the summary tables for consistency, and reported errors, which I corrected. Claude also identified related topics (Kaluza–Klein "bubbles of nothing", the Kasner conditions, Myers' theorem and the curvature test, Witten's instability) and wrote their descriptions and references. The Introduction and Summary was drafted by Claude from the notebooks under my direction.

## New to general relativity? A primer for students

If you have not yet studied general relativity, begin with the primer. It explains the metric, the field equations, and how the notebooks solve them, and works through two classic examples: the Schwarzschild–de Sitter solution and the expanding universe. *(Based on my earlier draft; edited and corrected by Claude.)*

- [Primer for Students (PDF)](0%20Primer%20for%20Students/Primer%20for%20Students.pdf)
- [Primer for Students (Word)](0%20Primer%20for%20Students/Primer%20for%20Students.docx)
- Worked example, Schwarzschild–de Sitter: [4D_b.pdf](0%20Primer%20for%20Students/4D_b.pdf) and [4D_b.nb](0%20Primer%20for%20Students/4D_b.nb)

## Start here: Introduction and Summary

This document summarizes all the cases in two tables, explains what the results mean, and includes a glossary with a worked 5D example.

- [Introduction and Summary (PDF)](1%20Introduction%20and%20Summary/Introduction%20and%20Summary.pdf): read it in the browser.
- [Introduction and Summary (Word)](1%20Introduction%20and%20Summary/Introduction%20and%20Summary.docx)

**Main findings:**

- Every case has exact solutions. Each comes in a standard form (GRW, generalized Robertson–Walker) and a free-gauge form (FG-GRW), which is the same spacetime in a more general radial coordinate.
- Requiring smoothness where a curled circle shrinks to zero size (a Kaluza–Klein "bubble of nothing") fixes a constant of the solution in closed form.
- A curvature test eliminates whole families. Curled spheres force the whole universe to be closed, with a size comparable to the sphere. Only the circle cases survive as candidates for our universe.
- In 7D_1 (three circles), the exponents of the solution obey the Kasner conditions of 1921.

These are simplified models (vacuum only, one scale factor, diagonal metrics), not yet realistic models of our universe. Section 8 of the Introduction and Summary lists the next steps.

## The case solutions

| Case | Curled space | Solution (PDF) | Mathematica notebook |
|---|---|---|---|
| 4D | none (the FLRW universe) | [4D.pdf](2%20Case%20Solutions%20%28PDF%29/4D.pdf) | [4D.nb](3%20Mathematica%20Notebooks/4D.nb) |
| 5D | circle S¹ | [5D.pdf](2%20Case%20Solutions%20%28PDF%29/5D.pdf) | [5D.nb](3%20Mathematica%20Notebooks/5D.nb) |
| 6D_1 | torus S¹×S¹ | [6D_1.pdf](2%20Case%20Solutions%20%28PDF%29/6D_1.pdf) | [6D_1.nb](3%20Mathematica%20Notebooks/6D_1.nb) |
| 6D_1 Appendix | why the 6D_1 assumptions are justified | [6D_1 Appendix.pdf](2%20Case%20Solutions%20%28PDF%29/6D_1%20Appendix.pdf) | [6D_1 Appendix.nb](3%20Mathematica%20Notebooks/6D_1%20Appendix.nb) |
| 6D_2 | 2-sphere S² | [6D_2.pdf](2%20Case%20Solutions%20%28PDF%29/6D_2.pdf) | [6D_2.nb](3%20Mathematica%20Notebooks/6D_2.nb) |
| 7D_1 | 3-torus S¹×S¹×S¹ | [7D_1.pdf](2%20Case%20Solutions%20%28PDF%29/7D_1.pdf) | [7D_1.nb](3%20Mathematica%20Notebooks/7D_1.nb) |
| 7D_2 | S²×S¹ | [7D_2.pdf](2%20Case%20Solutions%20%28PDF%29/7D_2.pdf) | [7D_2.nb](3%20Mathematica%20Notebooks/7D_2.nb) |
| 7D_3 | 3-sphere S³ | [7D_3.pdf](2%20Case%20Solutions%20%28PDF%29/7D_3.pdf) | [7D_3.nb](3%20Mathematica%20Notebooks/7D_3.nb) |

**How to read them:**

- **2 Case Solutions (PDF):** each notebook's output, laid out in textbook style. No software needed; GitHub shows PDFs in the browser.
- **3 Mathematica Notebooks:** the notebooks are ready to run from top to bottom. They can be modified to explore further cases, for example a separate scale factor for the curled dimensions, matter and radiation, or off-diagonal (rotating) metrics.
- **Without Mathematica:** the free [Wolfram Player](https://www.wolfram.com/player/) opens .nb files for reading.

## AI supplement: the circle cases (6D_1, 7D_1) with one assumption removed

*This supplement was generated by Claude (Anthropic). My part was the series of questions that led to it. I did not check the derivations myself, but I ran the verification notebook, and its outputs match the document.*

It asks what the torus cases would look like with four circles (8D_1), and what happens if the radial coefficient B is left free instead of being set to 1/(D₄D₅⋯). Leaving B free gives a larger family of solutions, but every new member has a curvature singularity; the only nonsingular ones are the GRW solutions of the main notebooks.

- [Torus Solutions Beyond GRW (PDF)](4%20AI%20Supplement%20-%20Torus%20Solutions%20Beyond%20GRW/Torus%20Solutions%20Beyond%20GRW.pdf)
- [Torus Solutions Beyond GRW (Word)](4%20AI%20Supplement%20-%20Torus%20Solutions%20Beyond%20GRW/Torus%20Solutions%20Beyond%20GRW.docx)
- [Verification notebook (Mathematica)](4%20AI%20Supplement%20-%20Torus%20Solutions%20Beyond%20GRW/Torus%20Solutions%20Beyond%20GRW.nb)
- [Verification notebook (PDF)](4%20AI%20Supplement%20-%20Torus%20Solutions%20Beyond%20GRW/Torus%20Solutions%20Beyond%20GRW%20-%20notebook.pdf)

## Notes for extending the notebooks

*Prepared by Claude (Anthropic) at my request.*

Metrics and field equations for the next steps, written in the notebooks' conventions so they can be entered directly: matter and radiation, rotation (the Kerr–de Sitter metric), two scale factors and Ricci-flat compact spaces such as Calabi–Yau spaces, and electromagnetism, both in four dimensions and from a curled Kaluza–Klein circle.

- [Extending the Notebooks (PDF)](5%20Notes%20for%20Extending%20the%20Notebooks/Extending%20the%20Notebooks.pdf)
- [Extending the Notebooks (Word)](5%20Notes%20for%20Extending%20the%20Notebooks/Extending%20the%20Notebooks.docx)

## Toward Calabi–Yau: two scale factors and the stabilization problem

A capstone for intermediate students. String theory curls six extra dimensions into a Calabi–Yau space, whose metric no one can write down. These notebooks show why cosmology does not need it: giving the curled space its own scale factor b(t), the field equations depend only on its dimension. They then show, in the simplest setting, the moduli-stabilization problem: with a positive cosmological constant, the curled space cannot keep a fixed size.

- [Toward Calabi–Yau: Introduction (PDF)](6%20Toward%20Calabi-Yau/Toward%20Calabi-Yau%20-%20Introduction.pdf) · [Word](6%20Toward%20Calabi-Yau/Toward%20Calabi-Yau%20-%20Introduction.docx) *(written by Claude at my request)*
- 6D, a torus with its own scale factor: [6D_1 Two Scale Factors.pdf](6%20Toward%20Calabi-Yau/6D_1%20Two%20Scale%20Factors.pdf) and [.nb](6%20Toward%20Calabi-Yau/6D_1%20Two%20Scale%20Factors.nb)
- 10D, six circles standing in for a Calabi–Yau space: [10D_1.pdf](6%20Toward%20Calabi-Yau/10D_1.pdf) and [10D_1.nb](6%20Toward%20Calabi-Yau/10D_1.nb)

*Role of AI: the notebooks are my own work. The connection to Calabi–Yau compactification and the direction of this section were suggested by Claude, which also checked the results.*

## Kaluza–Klein electromagnetism: the Coulomb law from a fifth dimension

The payoff that made Kaluza–Klein theory famous: momentum around a curled fifth dimension acts as electric charge. Part a adds a small cross term g₀₄ to the 5D Schwarzschild metric and recovers the Coulomb potential. Part b gives the exact solution, a black string boosted around the circle. Its charge is Q ∝ m sinh 2β, and the resulting 4D black hole carries a scalar (dilaton) field, so it is not Reissner–Nordström. Unlike the case solutions, this notebook is static and sets Λ = 0. It builds on 5D and on the Schwarzschild–de Sitter notebook 4D_b in the primer.

- [5D_b.pdf](7%20Kaluza-Klein%20Electromagnetism/5D_b.pdf) and [5D_b.nb](7%20Kaluza-Klein%20Electromagnetism/5D_b.nb)

*Role of AI: the notebook is my own work, following the Kaluza–Klein section of the Notes for extending the notebooks. Claude checked the results and the explanations.*

## License

GNU General Public License v3.0. See [LICENSE](LICENSE).
