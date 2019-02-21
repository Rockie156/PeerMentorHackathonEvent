---
layout: page
title: Puzzle
permalink: /puzzle/
---

## The Challenge

We've found some alien DNA!

Help us convert their genetic code to proteins.

The only difference is that rather than codons being independent units, it seems that aliens have overlapping codons. Additionally, the mapping is slightly more complex
than humans. 

While humans have a map of of for example GAA corresponds to Glutamic Acid, during Alien transcription the codon is actually sorted (by alphabetical order) into AAG which then corresponds to Lysine.
Additionally, the Aliens have a 'sliding scope' of view for DNA. Rather than codons being independent units, we shift one over.

For example, the following sequence:

ATGCC

results in the following codons:

ATG
TGC
GCC

Each codon is then sorted to

AGT
CGT
CCG

Which finally correspond to the amino acids:

Serine (S)
Arginine (R)
Proline (P)

Your job is to take a given string of DNA and output a string of amino acids.

Please keep in mind that there are two categories for submission: Fastest Code and Smallest Code.