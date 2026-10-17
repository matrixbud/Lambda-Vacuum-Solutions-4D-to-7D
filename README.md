# Exact Λ-Vacuum Solutions with Curled Extra Dimensions, 4D to 7D

**Harry S. (Bud) Simrin**

This repository contains exact solutions of Einstein's vacuum field equations with a cosmological constant,

**Rμν = Λ gμν**,

for an expanding universe in 4 to 7 spacetime dimensions. The extra dimensions are curled up into circles, tori, and spheres.

Every case is solved from scratch, one field equation at a time, in a Mathematica notebook that shows each step: setting up the metric, computing the Christoffel symbols and the Ricci tensor, and solving the field equations, with explanations along the way. The aim is to show *how* such solutions are found, including the dead ends, not just the finished results.

## Start here: the report

The report summarizes all the cases in two tables, explains what the results mean, and includes a glossary with a worked 5D example.

- [Report (PDF)](report/Lambda-Vacuum-Solutions-Report.pdf): read it in the browser.
- [Report (Word)](report/Lambda-Vacuum-Solutions-Report.docx)

**Main findings:**

- Every case has exact solutions. Each comes in a standard form (GRW, generalized Robertson–Walker) and a free-gauge form (FG-GRW), which is the same spacetime in a more general radial coordinate.
- Requiring smoothness where a curled circle shrinks to zero size (a Kaluza–Klein "bubble of nothing") fixes a constant of the solution in closed form.
- A curvature test eliminates whole families. Curled spheres force the whole universe to be closed, with a size comparable to the sphere. Only the circle cases survive as candidates for our universe.
- In 7D_1 (three circles), the exponents of the solution obey the Kasner conditions of 1921.

These are simplified models (vacuum only, one scale factor, diagonal metrics), not yet realistic models of our universe. The report's Section 8 lists the next steps.

## The notebooks

| Case | Curled space | Notebook | PDF |
|---|---|---|---|
| 4D | none (the FLRW universe) | [4D.nb](notebooks/4D.nb) | [4D.pdf](pdf/4D.pdf) |
| 5D | circle S¹ | [5D.nb](notebooks/5D.nb) | [5D.pdf](pdf/5D.pdf) |
| 6D_1 | torus S¹×S¹ | [6D_1.nb](notebooks/6D_1.nb) | [6D_1.pdf](pdf/6D_1.pdf) |
| 6D_1 Appendix | why the 6D_1 assumptions are justified | [6D_1 Appendix.nb](notebooks/6D_1%20Appendix.nb) | [6D_1 Appendix.pdf](pdf/6D_1%20Appendix.pdf) |
| 6D_2 | 2-sphere S² | [6D_2.nb](notebooks/6D_2.nb) | [6D_2.pdf](pdf/6D_2.pdf) |
| 7D_1 | 3-torus S¹×S¹×S¹ | [7D_1.nb](notebooks/7D_1.nb) | [7D_1.pdf](pdf/7D_1.pdf) |
| 7D_2 | S²×S¹ | [7D_2.nb](notebooks/7D_2.nb) | [7D_2.pdf](pdf/7D_2.pdf) |
| 7D_3 | 3-sphere S³ | [7D_3.nb](notebooks/7D_3.nb) | [7D_3.pdf](pdf/7D_3.pdf) |

**How to read them:**

- **PDF:** each notebook's output, laid out in textbook style. No software needed; GitHub shows PDFs in the browser.
- **Mathematica (.nb):** the notebooks are ready to run from top to bottom. They can be modified to explore further cases, for example a separate scale factor for the curled dimensions, matter and radiation, or off-diagonal (rotating) metrics.
- **Without Mathematica:** the free [Wolfram Player](https://www.wolfram.com/player/) opens .nb files for reading.

## License

GNU General Public License v3.0. See [LICENSE](LICENSE).
