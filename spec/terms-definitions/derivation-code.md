[[def: derivation-code, derivation code]]

~ To properly extract and use the [[ref: public-key-infrastructure]] embedded in a [[ref: self-certifying-identifier]] we need to know the cryptographic _signing scheme_ used by the [[ref: key-pair]]. KERI includes this very compactly in the identifier, by replacing the pad character (a character used to fill a void to able to always end up with a fixed length public key) with a special character that encodes the derivation process. We call this the _derivation code_.

~ More in <a href="https://weboftrust.github.io/WOT-terms/docs/glossary/derivation-code">extended KERI glossary</a>
