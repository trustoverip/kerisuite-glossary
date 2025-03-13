## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/authentic-web'>here</a>

## Related
- `Signed at rest` - the data never throws away any signature of data. Because otherwise we can't validate data in the future
- `Key state at rest` - you need to solve this hard problem too. This is the hard problem [KERI](KERI) solves.
- `Signed in motion` - signatures get thrown away. You use ephemeral identifiers. You have to do everything anew every time you want to reconstruct a verifiable data structure. Therefore we need 'Signed at rest'. 

- You can append to any part of the (directed-acyclic) [graph](directed-acyclic-graph)
- You can hop into the graph to verify any fragment of the graph
- You don't have to sign the data,you just have to sign hashes of this data
- Every tree that gets integrated in this giant graph-forest has its own [Root of Trust](root-of-trust)

KERI solves all hard problems of the authentic web in a scalable manner.

See more in [Concepts](https://weboftrust.github.io/keridoc/docs/concepts/concepts?level=2) behind KERI
