# Learning map

Rosalind is valuable because it connects biological questions to computational abstractions. This map groups the curriculum into reusable domains.

| Domain | Core ideas | Research connection |
|---|---|---|
| Sequences and formats | DNA/RNA/protein alphabets, FASTA, FASTQ, transformations | genome and read handling |
| Combinatorics and probability | recurrences, expectations, inheritance, random strings | population genetics and uncertainty |
| Motifs and string algorithms | k-mers, profiles, suffix structures, matching | regulatory motifs, markers, annotation |
| Graph algorithms and assembly | overlap/de Bruijn graphs, Eulerian traversal, contigs | genome assembly and pangenome graphs |
| Alignment and dynamic programming | edit distance, global/local alignment, gap models | homology and comparative genomics |
| Evolution and phylogeny | distances, trees, substitution, rearrangements | molecular evolution and phylogenomics |
| Mass spectrometry | spectra, peptide inference, graph search | proteomics |
| Clustering and HMMs | unsupervised learning, state models, decoding | gene prediction and sequence modeling |
| Tool literacy | Biopython, NCBI services, file-quality operations | reproducible day-to-day bioinformatics |

## How the domains reinforce one another

Assembly begins with sequence data and k-mers, uses graphs to resolve paths, and needs quality checks to judge output. Comparative genomics then uses alignment and phylogeny to distinguish shared ancestry from unrelated similarity. Pangenomics extends this reasoning across many genomes, where gene presence–absence, sequence variation, and graph structure must be interpreted together.

## Suggested study cadence

For each private exercise:

1. State the biological question in one sentence.
2. Identify the data structure and computational pattern.
3. Implement from first principles.
4. Test ordinary, boundary, and adversarial inputs.
5. Record complexity and failure modes.
6. Submit to Rosalind.
7. Transfer only the general insight into this public atlas.

This keeps the project educational, scientifically honest, and useful beyond any one platform.
