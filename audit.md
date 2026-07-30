# Audit

Dated log of editorial passes and verification runs. Newest first.
See the workspace docs (run `papers docs`): writing-pipeline.md §7 and refresh-pipeline.md.

## 2026-07-29 — first draft, research, and publish

Scope: the whole paper, from the seeded chat to a published PDF and a web entry.

Origin: `chats/chat.md`, a research brief proposing a sociological account of pigeons from domestication to pest status, with a recommended title, a draft abstract, a draft opening, an empirical research design, and an annotated bibliography. The brief's conceptual moves (distributed decommissioning, the trait inversion, non-place as species-relative) were adopted. Its proposed ethnographic design was not, since this is a genealogy rather than a fieldwork paper. Its instruction that the contemporary resonance stay implicit was followed literally: the paper names no present-day case, and the closing paragraph generalizes structurally without allegory.

What the paper adds to the brief:

- **The central result.** The brief described a process; the paper states conditions. Terminal state is fixed by enumerability and standing obligation, the four cells are each instantiated, and three of them are enacted in statute. This is the section the brief did not have.
- **The horse as control condition.** The urban horse was decommissioned faster and more completely and left no feral population, which dissolves the trait explanation and isolates collectability as the variable.
- **The Army's own pigeons as the internal control.** The same species, decommissioned twice, once with an inventory (1957, ended cleanly) and once without (the street).
- **The trait inversion as a documented textual fact** rather than a rhetorical table, carried by the wildlife-damage handbook explaining its own difficulties by naming the products of domestication.
- **Two deflations.** The 1.1 billion dollar damage figure traced to its arithmetic, and the health risk given its measured size.
- **The Palmerston provenance.** "Matter out of place" was first recorded in an argument about returning urban waste to farmland, which is the dovecote's economy, so the Douglas citation does work instead of decorating.

Changes:
- `brief.md`, `research.md`, `sources.md` written; `paper/PAPER.md` drafted at 6,644 words across 8 sections and 2 tables; `README.md`, `metadata.yaml` (title, header, date, abstract, status) filled; `build.py` vendored.
- Two voice fixes after the first gate run: a negate-then-pivot at the end of §2 and another in the closing paragraph were rewritten as positive declaratives; four spelled quantities converted to numerals; three short sentences added to break a 24-sentence run with none short.

Research and verification:
- Six parallel verification fan-outs, each required to return exact locators and to mark what it could not confirm. Statutes (P.L. 92-195, 106-446, 106-551) were read from the Statutes at Large facsimiles; the Williams and Corrigan handbook chapter was retrieved and read in full; Skinner (1960), Darwin (1868), Tepper et al. (2018) and Jerolmack (2008) were read rather than summarized.
- Errors caught in the seed material and in circulating citations: Petty (2016) is in *International Journal for Crime, Justice and Social Democracy* 5(1), not *IJLBE* 8(1); the Larson and Fuller proof PDF prints a DOI belonging to a different article; Carter et al. is 2026 First View with no volume; Blattner, Coulter and Kymlicka is 2019 in print; the Wild Free-Roaming Horses and Burros Act was approved 15 December 1971, not 18 December.
- Sources dropped rather than softened, with reasons recorded at the foot of `sources.md`: Levi (1941), the husbandry half of the inversion, unobtainable; Basel's population figures, untraceable to the primary paper; Trafalgar Square's pre-ban counts, journalistic; Rosenberger on bird spikes, unfound; the Isfahan "14,000 birds per tower" figure, untraceable.
- Prior-art checks on the paper's three coinages: "pestification" is already used in plant pathology (Saleh et al., 2014; De Gracia et al., 2015) and the paper acknowledges the prior sense and distinguishes its own; "distributed decommissioning" and "feral nonspace" returned no scholarly usage.

Verification:
- voice: 0 errors, 0 review-candidates. Advisories: lexical density within corpus norms (carries/carry 0.8/k, tricolons 2.9/k); rhythm 254 sentences, mean 25 words, sd 17, 16 per cent short, longest run without a short one 17.
- refs: 49 in-text citation keys, 50 bibliography entries, 0 missing, 0 unused.
- claims: `claims_target: none`; no simulation, so every factual claim is carried by `sources.md` instead.
- build: 17 pages, 0 missing-character warnings, both pipe tables render, title page breaks cleanly across two lines.
- check => PASS. Synced to the web app; entry added to `ownPapers` with topics sociology / history / biology and kinds genealogy / essay.
