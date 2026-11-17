# Column types under ring switching

Andrei Kochergin, 15 November 2026. Read it as a [PDF](column-types-ring-switching.pdf) or as an
[article on oumuamua.dev](https://oumuamua.dev/blog/column-types-ring-switching).

## Abstract

A commitment over $\mathbb{F}_{2^{128}}$ binds a committed cell only to $\mathbb{F}_{2^{128}}$, while the type of
a column may declare the field of a bit or a byte. We batch the claims on each column by ring switching over its
declared field, and prove that an accepted proof binds every cell of a committed column to that field. The result
holds at multilinear and at univariate-skip points and draws eight more challenges.

## Revisions

The first revision, of 15 November 2026, describes the type binding of Hekate v0.39.

## Citation

```bibtex
@misc{kochergin2026columntypes,
  author       = {Andrei Kochergin},
  title        = {Column types under ring switching},
  howpublished = {Oumuamua Labs library},
  year         = {2026},
  url          = {https://github.com/oumuamua-labs/library/tree/main/hekate/column-types-ring-switching},
}
```