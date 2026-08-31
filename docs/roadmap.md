# Build roadmap

This roadmap separates **mastery**, **evidence**, and **public communication**. The work is deliberately organized by transferable algorithmic ideas rather than by a random sequence of exercise IDs.

## Phase 1 — Foundation and audit

**Outcome:** a reliable project architecture with a clear distinction between public learning materials and private exercise work.

- [x] Audit the original repository materials
- [x] Establish public scope and integrity policy
- [x] Map the five official Rosalind tracks
- [ ] Create the private implementation workspace
- [ ] Add a machine-readable private progress ledger
- [ ] Establish test and submission-verification conventions

## Phase 2 — Sequence foundations

**Outcome:** fluency with representations, parsers, simple transformations, and correctness testing.

- DNA, RNA, and protein sequence representations
- FASTA and FASTQ parsing
- reverse complements, transcription, translation, codons
- GC content, Hamming distance, motif positions
- recurrence relations and basic probability
- complexity analysis and boundary conditions

**Applied bridge:** quality-aware sequence summaries and microbial genome composition.

## Phase 3 — Motifs, strings, and graphs

**Outcome:** a practical toolkit for pattern discovery and sequence-graph reasoning.

- k-mers, profiles, consensus, and motif search
- tries, suffix structures, Burrows–Wheeler transform
- overlap graphs, de Bruijn graphs, Eulerian paths
- contig construction and assembly quality

**Applied bridge:** simulated read assembly and graph inspection for accessory loci.

## Phase 4 — Dynamic programming and alignment

**Outcome:** understanding alignment as an explicit scoring and optimization problem.

- edit distance and longest common subsequences
- global, local, overlap, semiglobal, and affine-gap alignment
- multiple alignment concepts
- scoring matrices, traceback, and optimal-solution counting

**Applied bridge:** compare native implementations against established libraries on controlled examples.

## Phase 5 — Evolution, populations, and phylogeny

**Outcome:** connect sequence variation to evolutionary inference.

- substitution models and distance matrices
- Newick parsing, tree distances, character tables
- UPGMA and neighbour joining
- Mendelian and Wright–Fisher probability models
- genome rearrangements and comparative structure

**Applied bridge:** small, transparent phylogenetic analysis with sensitivity checks.

## Phase 6 — Peptides, clustering, and HMMs

**Outcome:** broaden algorithmic reasoning beyond nucleotide sequences.

- mass-spectrum graphs and peptide inference
- hierarchical clustering
- hidden Markov models and decoding
- profile models and probabilistic sequence analysis

## Phase 7 — Tooling and reproducibility

**Outcome:** make every reusable method inspectable and repeatable.

- Python package layout and command-line interfaces
- unit, property, and regression tests
- formatting, linting, typing, and continuous integration
- pinned environments and provenance records
- benchmark inputs distinct from Rosalind datasets

## Phase 8 — Applied microbial-genomics capstone

**Outcome:** demonstrate transfer from algorithm practice to a biologically motivated workflow.

The final public capstone will use original or openly licensed data to connect sequence similarity, graph concepts, gene presence–absence, and phylogenetic context in microbial pangenomics. It will not reuse Rosalind challenge datasets or present challenge-answer code.

## Definition of progress

| Label | Meaning |
|---|---|
| Mapped | Concept and official exercise are placed in the private curriculum |
| Implemented | An original private implementation exists |
| Tested | Independent tests and edge cases pass |
| Verified | A Rosalind submission has been accepted |
| Transferred | The concept appears in an original public note or capstone |

Only **Verified** tasks count toward private Rosalind completion. Only **Transferred** concepts appear in public portfolio work.
