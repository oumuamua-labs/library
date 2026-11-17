# Zero-knowledge folding of tables of different heights

Andrei Kochergin, 12 November 2026. Read it as a [PDF](zk-folding.pdf) or as an
[article on oumuamua.dev](https://oumuamua.dev/blog/zk-folding).

## Abstract

One fold of the BaseFold and FRI-Binius kind commits tables of different heights with the binding error of a
single fold over the tallest table. We make this fold zero knowledge, with an outer zero-knowledge argument for
the scalars it publishes. When the fold halves the height $a$ times between commitments and the verifier makes
$t$ queries, zero knowledge costs two uniform polynomials over $\mathbb{F}_{2^{128}}$, $2^a$ times shorter than
the largest, and $(t + 2)\,2^a + 1$ uniform cells or fewer at the start of every other polynomial.

## Revisions

The first revision, of 12 November 2026, describes the fold commitment of Hekate v0.39.

## Citation

```bibtex
@misc{kochergin2026zkfolding,
  author       = {Andrei Kochergin},
  title        = {Zero-knowledge folding of tables of different heights},
  howpublished = {Oumuamua Labs library},
  year         = {2026},
  url          = {https://github.com/oumuamua-labs/library/tree/main/hekate/zk-folding},
}
```