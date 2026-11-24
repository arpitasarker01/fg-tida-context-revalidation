# TIDA Specification Template

<!-- Keep the two sections below in every repository created from this template. Once a work item is created, replace everything below the horizontal line with the metadata of the work item. -->

## Propose a new work item

Want to propose a new work item (NWI) to FG-TIDA? Follow the procedure in the contribution guide: https://fg-tida.github.io/.github/#new

## Contribute to this work item

Contributions to the work of a Working Group are possible once a work item has been adopted by that Working Group and its official repository has been created. The instructions are in the contribution guide: https://fg-tida.github.io/.github/#existing

Anything you contribute is offered as input to the Working Group's work and may be incorporated into its deliverables. Participation follows the ITU-T and FG-TIDA participation, conduct, and IPR rules.

---

## Technical contribution

Context-Bound Authority Applicability and Human Decision Revalidation in Agentic AI

Candidate technical requirements and assessment cases derived from UC-6. Proposed technical input, version 0.1, 24 November 2026; not adopted. Author: Arpita Sarker, Forkit AI. Working-group allocation pending.

The RST source is in `src/doc`, with entry document `src/doc/index.rst`. All document assets are within that folder. The template build dependencies, theme, and workflows are retained. See [CONTRIBUTING.md](CONTRIBUTING.md) for build instructions.

## Source provenance

Converted from the user-supplied `FG-TIDA_Arpita_Sarker_Paris_Submission_v0.1.docx` without substantive text changes. Its filename does not include `_FINAL`; no separate `_FINAL.docx` was available for comparison.

- DOCX SHA-256: `a709d6f23d098e082b2bbd0ddff7863a6b3dc3c32a8be33c5eba30674dd788c5`
- Embedded PNG SHA-256: `c549bf3259a13fe97244a69c0971fc37f7ce8341bb0c7f5d7093bda767be138c`
- Preserved: six tables (including History and Authors), one embedded diagram, all six technical sections and fifteen informative references.

No DataTracker submission has been made.

## Validation

The converted source passed Sphinx HTML and LaTeX generation with warnings treated as errors. Every source paragraph and every table cell was checked against the rendered HTML after whitespace normalization. The embedded diagram is byte-identical to the DOCX image, and all seven HTML pages were visually reviewed. Template examples, their sample diagram, and the sample API definition were removed. Theme assets, dependencies, and workflows are unchanged; document metadata and cover labels identify this as a proposed technical contribution.

A complete PDF compilation was not performed locally because LaTeX/latexmk are not installed. The retained GitHub Actions workflow provides the template's full HTML/PDF build. GitHub Pages deployment requires the repository's Pages source to be configured for GitHub Actions. The inherited GitLab synchronization workflow requires its own secrets and is separate from document validation.
