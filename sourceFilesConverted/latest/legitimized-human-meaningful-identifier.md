## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/legitimized-human-meaningful-identifier'>here</a>

## Problematic human meaningfulness
Human meaningfulness has two limiting characteristics: *scarcity* and *security*. Scarcity exhibits itself in various undesirable ways such as name squatting, or race conditions to register or otherwise assert control. More importantly, there is no inherent security property of a human meaningful identifier. This makes them insecure by default. Happily an [AID](autonomic-identifier) comes to rescue.

The trust domain of an AID provides a context in which to interpret the appearance of any LID. The AID is implied by the context. This means that the AID may not need to be prepended or appear with the LID. This allows the human meaningfulness of the LID to exhibit itself without being encumbered by the AID.

This model of an *aid|lid couplet* unifies all desirable identifier properties into one identifier system model. The AID part provides the security infrastructure while the LID part provides the application specific human meaningfulness. The connection between the two is provided by a legitimizing authorization represented by the |.
