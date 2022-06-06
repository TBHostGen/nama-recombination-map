# Nama recombination map

## Introduction
This repository contains an inferred recombination map (hg19) for the Nama.
The map was inferred using [pyrho](https://github.com/popgenmethods/pyrho) and demographic history (used by pyrho) was inferred using [SMC++](https://github.com/popgenmethods/smcpp) and [AS-IBDNe](https://github.com/hennlab/snake-IBDne).

Files prefixed with raw are the raw output files from pyrho and contain the recombination rate per base pair per generation for a given window.

Files prefixed with nama contain the base pair position as its first column, the recombination rate in cM/Mb as its second column and the genetic position in cM as its third column.

## Citation
https://www.biorxiv.org/content/10.1101/2021.11.07.467603v1.full.pdf
