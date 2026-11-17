# Folding tables of different heights at the Johnson radius

Andrei Kochergin, 15 November 2026. Read it as a [PDF](folding-johnson-radius.pdf) or as an
[article on oumuamua.dev](https://oumuamua.dev/blog/folding-johnson-radius).

## Abstract

We prove that one BaseFold-style fold over tables of different heights binds every accepted claim to a short list
of tables at the Johnson radius. Its error is Haböck's list-decoding error for one fold at the largest height,
plus the list size times the errors of the earlier draws. For 128 bits this takes 262 queries at rate $1/2$ and
130 at rate $1/4$.

## Revisions

The first revision, of 15 November 2026, describes how Hekate v0.39 counts its fold queries.

## Citation

```bibtex
@misc{kochergin2026johnson,
  author       = {Andrei Kochergin},
  title        = {Folding tables of different heights at the Johnson radius},
  howpublished = {Oumuamua Labs library},
  year         = {2026},
  url          = {https://github.com/oumuamua-labs/library/tree/main/hekate/folding-johnson-radius},
}
```