[[def: cold-start-stream-parsing, cold start stream parsing]]

~ After a reboot (or cold start), a stream processor looks for framing information to know how to parse groups of elements in the stream. 

~ If that framing information is ambiguous then the parser may become confused and require yet another cold start. While processing a given stream a parser may become confused especially if a portion of the stream is malformed in some way. This usually requires flushing the stream and forcing a cold start to resynchronize the parser to subsequent stream elements. 

~ More in <a href="https://weboftrust.github.io/WOT-terms/docs/glossary/cold-start-stream-parsing">extended KERI glossary</a>
