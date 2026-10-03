# DM42 Solver Handbook

A practical, example-driven guide to mastering the SwissMicros DM42 Solver, from first principles and complete keystrokes to advanced real-world models.

[Download the handbook (PDF)](./DM42_Solver_Handbook.pdf)

## About the handbook

The **DM42 Solver Handbook** explains how to turn an equation into a residual, build a reusable Solver program, choose useful starting estimates, interpret Solver messages, and verify that a numerical result is both mathematically and physically meaningful.

It is written for novice, intermediate, and experienced DM42 users. The early chapters develop the method with deliberately simple examples; later chapters apply the same workflow to increasingly demanding problems.

## Contents

- **Part I — Understanding the Solver**: residuals, roots, estimates, domains, discontinuities, scaling, and verification.
- **Part II — Building a Solver Program**: labels, `MVAR` declarations, RPN stack planning, program entry, testing, and reuse.
- **Part III — Trivial Examples That Build Fluency**: small, fully worked exercises with complete keystrokes.
- **Part IV — Intermediate Examples**: more substantial applications and model-building practice.
- **Part V — Advanced Examples**: nonlinear equations, coupled effects, transformed variables, and more demanding domains.
- **Part VI — Advanced Techniques**: robust modelling, multiple roots, reusable subroutines, diagnostics, and numerical judgement.
- **Part VII — Extreme Case Studies**: extended models that combine several Solver techniques.
- **Appendices A–N**: quick reference material, program templates, common functions, glyphs, constants, troubleshooting, indexes, glossary, and bibliography.

The worked examples span mathematics, classical physics, astrophysics, chemistry, biology, finance, logistics, game theory, engineering, electronics, and thermal and fluid systems.

## Keystroke notation

The handbook distinguishes between calculator keys, menu choices, typed names, and stored program instructions:

| Form | Meaning |
| --- | --- |
| `[KEY]` | Physical or shifted calculator key |
| `{MENU}` | Soft-key label shown on the display |
| `(TEXT)` | Literal alpha text followed by `ENTER` |
| `01 instruction` | Stored program line |

In Program mode, ordinary instructions are entered with their physical keys or menu soft keys. Pressing `[XEQ]` creates an actual `XEQ` instruction, so it is used only when a program must call a labelled routine or subroutine.

## Using the handbook

1. Download or open [`DM42_Solver_Handbook.pdf`](./DM42_Solver_Handbook.pdf).
2. Work through Parts I and II in order if the Solver is new to you.
3. Enter the early example programs exactly as shown and verify their listings line by line.
4. Compare every Solver result with the verification value or substitute it back into the original equation.
5. Use the later chapters and appendices as a reference when building your own models.

## Contributing

Corrections and improvements are welcome. When reporting a problem, please include:

- the PDF page and section;
- the program line or keystroke sequence involved;
- the observed DM42 behaviour;
- the expected behaviour; and
- the calculator firmware version, when relevant.

Please use an issue for isolated corrections and a pull request for proposed file changes.

## Disclaimer

This is an independent, unofficial educational resource. It is not affiliated with or endorsed by SwissMicros. Product and company names belong to their respective owners. Numerical examples should be independently checked before being used for consequential engineering, financial, scientific, or safety-related work.
