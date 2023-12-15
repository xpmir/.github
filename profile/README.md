## XPMIR experimental repositories

This workspace contains repositories with experiments relying on [experimaestro-ir](https://github.com/experimaestro/experimaestro-ir)

[A template project](https://github.com/xpmir/experiment-template) is available.

Experiments can be run with

```sh
xpmir run-experiment PATH_TO_DEFINITION.yaml
```
where  `PATH_TO_DEFINITION` is given in the list of implemented papers.

### [Cross-Encoders](https://github.com/xpmir/cross-encoders)

- `monobert/normal`: [monoBERT](https://github.com/xpmir/cross-encoders/tree/main/monobert) described in [^monobert]
- `monot5/normal`

### [SPLADE](https://github.com/xpmir/splade)

- `splade/normal_DistilMSE`: SPLADE-max with MSE distillation from https://github.com/sebastian-hofstaetter/neural-ranking-kd

[^splade]: From Distillation to Hard Negative Sampling: Making Sparse Neural IR Models
    More Effective (Thibault Formal, Carlos Lassance, Benjamin Piwowarski
[^monobert]: Passage Re-ranking with BERT (Rodrigo Nogueira, Kyunghyun Cho. 2019](https://arxiv.org/abs/1901.04085)


