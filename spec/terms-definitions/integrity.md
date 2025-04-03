[[def: integrity]]

~In KERI's "security first" approach Authenticity includes _technical integrity_ of data involved. This includes:
1. [[ref:internal-inconsistency]]
2. External consistency or [[ref:duplicity]] evident

~ Integrity in ACDCs is "self-verifying": the [[ref:self-addressing-identifier)]] that is contained in the data is also the of hash of the data.

~ The integrity of streaming data in [[ref:composable-event-streaming-representation]] and [[ref:cesr-proof-signatures]] is established by code tables and verifiable by the mere (killer-)feature: round-robin [[ref:composability]]. If you can toggle between the text - and binary representation, _then that's the integrity proof_, if not, then it's provably lacking integrity.

~ A side-benefit of how integrity is implemented in KERI is [non-repudiation](non-repudiable) - done via a crypto-hash verification via the signer's public key - is not inherent in the meaning of integrity.

~ Furthermore for KERI integrity, as an assessment of the substance or the content itself, does not fall within its narrow definition. **Our criterium is cryptographic verifiability**. Once you can't verify, for KERI this type of non-technical integrity is not included in `integrity`. For the same reason we wouldn't use [validation](validate)* as a mechanism to prove integrity.


~ Integrity (of a message or data) means that the information is whole, sound, and unimpaired (not necessarily correct). It means nothing is missing from the information; it is complete and in intended good order.  
~ Source: Neil Thomson

~ More in <a href="https://weboftrust.github.io/WOT-terms/docs/glossary/integrity">extended KERI glossary</a>
