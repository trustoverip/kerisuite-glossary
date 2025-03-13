## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/cold-start-stream-parsing'>here</a>

## re-synchronization
Better than flushing the stream and forcing a cold start is a re-synchronization mechanism that does not require flushing the in-transit buffers but merely skipping to the next well-defined stream element boundary in order to execute a cold start.   
_See an example_ in the [source](https://github.com/WebOfTrust/ietf-cesr/blob/main/draft-ssmith-cesr.md#cold-start-stream-parsing-problem)

Special CESR count codes support re-synchronization at each boundary between interleaved CESR and other serializations like JSON, CBOR, or MGPK.