# FlexAlloc: Dynamic Memory Partioning between the Hostvisor and Corevisor in SeKVM

This repository contains the TeX files used to generate the FlexAlloc research paper. For the FlexAlloc source code, see [this repository](https://github.com/nelsonm2991/host-sekvm-project).

## Usage

To compile the paper, run:

```bash
rm -rf paper.bib
pdflatex paper      # Generate paper.bib
bibtex paper
pdflatex paper      # Compile with paper.bib
```

## Dependencies

You will probably need to use a package manager to manage the `TeX` dependencies. We used `tlmgr`, which worked pretty well for us.

Some packages you will probably need:
- breakurl
- courier (install this if you see that ucrr8a.pfb is missing)
- filecontents
