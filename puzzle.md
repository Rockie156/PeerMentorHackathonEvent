---
layout: page
title: Puzzle
permalink: /puzzle/
---
We've found some alien DNA!

Help us convert translate their genetic code into amino acids.

The aliens appear to have two key differences:

1. Their codons overlap rather than being next to each other.
2. Their enzymes sort codons before transcribing them to amino acids

### Example Trace
Consider the following DNA sequence

```
ATGCC
```

Which produces the following codons (observe how each codon lines up with the original):

```
ATGCC (original, not a codon)
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

Which (after performing a lookup [here](https://en.wikipedia.org/wiki/DNA_codon_table)) results in:

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
### Restrictions
This challenge MUST be written in python3! We will be using tio.run to evaluate answers. Please view [this link](https://tio.run/##ZVHLTsMwELz7K1buoYlURSBuSDlUIHpDCHpBCFWm2SSGeB3ZG0r4@WDnQQ@9OJtdz8zOuO25tnQzDCt4sQahauyHajwYXdUMlYUaHQofRodpBDnI3XxJOaQ1g2pOqvfANYK3TcfakhRiBa@2c1B2dIydwIV@YiuwBHaKfGmdSX7SWwEgpYSHi6uxHYYOuXME66IzpgfPTlO1HrRprWMIRIU1Yv7zvRejQIWETjEeNLUdJ/Sv8jySheVnIjhaYqUplmpmA81oPJQulN@q6cI6J801NEhV@NC81zzK4U1u5QbkPh67eNzJ9/PeUmafVlMycWfH2uoj@mRCb@ArpzSNee2QxxBnFVtCDPD@cQtembZBQUFKEyfBZOa50JQ5VEWyoCfDZxMTKvJ4/YtAIlLll8lE9H55j2A9alhonWXU5MVSBOj51QLViHsKEfKIKYEw2PLK9aHfxn6yQNPh@uoP) for a sample.
Only the 'Code' section will be counted towards the size category.

### Resources
You are encouraged to use the internet! Please feel free to use any resources you'd like.

# Submission
Please keep in mind that there are two categories for submission: Fastest Code and Smallest Code. We will be collecting solutions the day of the event and showcasing and discussing them. You <b>must</b> attend to be eligible for prizes.