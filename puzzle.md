---
layout: page
title: Puzzle
permalink: /puzzle/
---

We've found some alien DNA!

Help us convert their genetic code to proteins.

The aliens appear to have two key differences:

1. Their transcription enzyme shifts only 1 base rather than 3 (each codon is still 3 base pairs long).
2. Their enzymes sort codons before transcribing them to amino acids!

### Example Trace
For example, the following sequence:

```
ATGCC
```

results in the following codons:

```
ATG
TGC
GCC
```

Each codon is then sorted to

```
AGT
CGT
CCG
```
Which finally correspond to the amino acids:

```
Serine (S) 
Arginine (R)
Proline (P)
```

### Example Output
Your job is to take a given string of DNA and output a string of amino acids.

```
SRP
```

### Resources
The codon conversion table can be found here: https://en.wikipedia.org/wiki/DNA_codon_table

# Submission
Please keep in mind that there are two categories for submission: Fastest Code and Smallest Code. We will be collecting solutions the day of the event and showcasing and discussing them. You <b>must</b> attend to be eligible for prizes.