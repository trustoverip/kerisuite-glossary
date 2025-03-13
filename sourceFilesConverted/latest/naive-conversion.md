## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/naive-conversion'>here</a>

## Why naive

Naive conversion is a text to binary conversion or vice versa that doesn't anticipate on either [composability](composability) and / or on the [concatenation](concatenation) capability of the result of such an operation.

In the [IETF draft CESR](https://github.com/WebOfTrust/ietf-cesr/blob/main/draft-ssmith-cesr.md#conversions) there's much attention for naive [Base64](base64) conversions, because it helps explaining the necessity of stable code characters and padding in CESR to achieve:
- [self-framing](self-framing)
- round-robin [composability](composability)
- [concatenation](concatenation) options
- [pipelined](pipelining) streaming
