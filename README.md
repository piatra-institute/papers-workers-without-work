# Workers Without Work

Pigeons and the Infrastructural Afterlife of Domestication.

When an institution stops needing an animal's work, the lives organized around that work continue. Pigeons show the mismatch clearly: their capacities for homing, reproduction and life near people outlasted many of the institutions that employed them. We trace the withdrawal of those institutions through histories of pigeon keeping, disposal records, animal retirement statutes and the urban control literature, and call their uneven retreat *distributed decommissioning*. Comparisons with horses, military dogs and research chimpanzees separate the power to dispose of a worker from the acceptance of responsibility after work. Sale, adoption, sanctuary and statutory protection of unowned populations are distinct settlements, and the disappearance of a task determines none of them. The pigeon record also shows a capacity once valued as a service, reliable homing, becoming an objection to the continued presence of the birds that have it. Ecology and material harms shape this process, yet neither population counts nor control costs settle the question of obligation. The argument rests on the difference between arranging another use for an animal and recognizing a claim that no longer depends on its usefulness.

## Read and check

- [Manuscript](paper/PAPER.md) and [local PDF](paper/PAPER.pdf).
- [Editorial decisions](editorial.md) and [current brief](brief.md).
- [Bound claims](claims.yaml) and [structured bibliography](references.json).
- [Source checks](source-checks.md). Earlier research remains in research.md and
sources.md as dated provenance, not as a current verification certificate.

No simulation is used. Numbers come from identified historical or scientific sources. Definitions, interpretations and ethical premises are recorded separately. The concluding use of membership is normative, not a claim of legal citizenship.

## Build

From this repository, with Pandoc and XeLaTeX installed:

```sh
python3 build.py
```

From the collection root:

```sh
python3 tooling/papers.py check workers-without-work --stage local
```

The title page separates title and subtitle, followed by PIATRA . INSTITUTE and the date. The build log and manifest are generated locally and ignored by Git. A local build does not publish or update the website.
