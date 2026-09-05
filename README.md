# Workers Without Work

Pigeons and the Infrastructural Afterlife of Domestication.

What remains owed when a function disappears but the lives organized around it
continue? Pigeons provide the historical case. Their work brings together lofts,
keepers, contracts and institutions; the end of that work leaves questions that
a sale, a closure date or a new technology cannot answer alone.

The paper distinguishes finding another use for an animal from recognizing a
claim that no longer depends on usefulness. Comparisons with horses, military
dogs and research chimpanzees show different settlements of custody and
responsibility. They do not establish a universal law of animal populations.

## Read and check

- [Manuscript](paper/PAPER.md) and [local PDF](paper/PAPER.pdf).
- [Editorial decisions](editorial.md) and [current brief](brief.md).
- [Bound claims](claims.yaml) and [structured bibliography](references.json).
- [Source checks](source-checks.md). Earlier research remains in research.md and
  sources.md as dated provenance, not as a current verification certificate.

No simulation is used. Numbers come from identified historical or scientific
sources. Definitions, interpretations and ethical premises are recorded
separately. The concluding use of membership is normative, not a claim of legal
citizenship.

## Build

From this repository, with Pandoc and XeLaTeX installed:

```sh
python3 build.py
```

From the collection root:

```sh
python3 tooling/papers.py check workers-without-work --stage local
```

The title page separates title and subtitle, followed by PIATRA . INSTITUTE and
the date. The build log and manifest are generated locally and ignored by Git.
A local build does not publish or update the website.
