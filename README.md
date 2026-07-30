# Workers Without Work

Pigeons and the Infrastructural Afterlife of Domestication. The paper asks why the withdrawal of every institutional function from a domestic animal produced, in the twentieth-century city, a pest rather than an absence. It names the process *distributed decommissioning*: the piecemeal withdrawal of functions, provisioning and responsibility from a living human-made population by unrelated institutions, none of which ever held the whole population, so that no actor ever had to declare the birds feral and none inherited them. Its central result is that the terminal state of a decommissioned working-animal population is fixed by two institutional variables rather than by the animal's traits, namely whether the population stays enumerable and whether any institution keeps a standing obligation to it. All four combinations occur in the record and three are written into statute: military working dogs are adopted at the end of their useful working life, research chimpanzees enter a sanctuary that may not discharge them, and unbranded and unclaimed horses on the public range were declared living symbols and protected from capture and death. The Army's own pigeons, being listed, ended cleanly in 1957; the urban horse, owned to the last day and worth money as a carcass, left no feral population; the street pigeon was reachable by no decision and worth nothing dead. The paper then shows the reversal of the animal's capacities documented inside the wildlife-damage literature, which explains the impracticality of release by naming homing, reads pest status as a relation among recognized utility, ownership and spatial authorization that dissolves when any one term is restored, traces the canonical billion-dollar damage figure back to an assumed cost per bird multiplied by an assumed bird per hectare, and closes on *feral nonspace*, anthropogenic space that is materially habitable and institutionally disavowed as habitat, held that way by a continuous expenditure on spikes patented in 1939.

## Sources

No simulation. Every factual claim traces to a source frozen in `sources.md`, with the tiering and the exact locators in `research.md`; sources that could not be verified were dropped rather than softened, and the casualties are listed at the foot of `sources.md`.

## Build

```bash
uv run build.py          # -> paper/PAPER.pdf  (vendored canonical recipe)
```

Requires `pandoc` and `xelatex` on PATH. From the workspace you can also run
`papers build workers-without-work`.

Part of [piatra-papers](https://github.com/piatra-institute). See the workspace
docs for the research and writing pipelines.
