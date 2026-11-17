# A note on zero-knowledge ring switching

Andrei Kochergin, November 2026, [ePrint 2026/2754](https://eprint.iacr.org/2026/2754). Read the
[PDF](zk-ring-switching.pdf).

## Abstract

We make the ring-switching technique of Diamond and Posen zero knowledge, resolving a problem left open in the
literature. Over $\mathbb{F}_{2^n}$, our technique uses $n-1$ auxiliary masks and $n-1$ quadratic constraints,
checked in zero knowledge by the underlying commitment scheme.

## Revisions

The second revision, of November 2026, is the one on ePrint and in this folder. The first,
[Zero-Knowledge Ring-Switching without the Transpose](https://oumuamua.dev/blog/zk-ring-switching), of September
2026, stays as published on oumuamua.dev. Hekate has made its ring switching zero knowledge since v0.34, with the
construction of the first revision.

## Citation

```bibtex
@misc{cryptoeprint:2026/2754,
  author       = {Andrei Kochergin},
  title        = {A note on zero-knowledge ring switching},
  howpublished = {Cryptology {ePrint} Archive, Paper 2026/2754},
  year         = {2026},
  url          = {https://eprint.iacr.org/2026/2754},
}
```