## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/nested-cooperative-delegated-identifiers'>here</a>

## More

Each commitment is signed respectively by the committer. This cooperative delegation together with special superseding recovery rules for events enables cooperative recovery.

This superseding rule may be recursively applied to multiple levels of delegation, thereby enabling recovery of any set of keys signing or pre-rotated in any lower levels by a superseding rotation delegation at the next higher level. This cascades the security of the key management infrastructure of higher levels to lower levels. This is a distinctive security feature of the cooperative delegation of identifiers in KERI.

More in chapter Nested Delegation Recovery of the [whitepaper](https://github.com/SmithSamuelM/Papers/blob/master/whitepapers/KERI_WP_2.x.web.pdf)