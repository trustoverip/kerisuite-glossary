[[def: sniffable, sniffable]]

~ A stream is _sniffable_ as soon as it starts with a group code or field map; in fact this is how our parser ([[ref: parside]]) works. and detects if the CESR stream contains a certain datablock. 
~ The datablock of CESR binary, CESR Text, JSON, CBOR, MGPK have an Object code or the Group code (binary or text) and it's always a recognizable and unique _three bit combination_.

~ More in <a href="https://weboftrust.github.io/WOT-terms/docs/glossary/sniffable">extended KERI glossary</a>
