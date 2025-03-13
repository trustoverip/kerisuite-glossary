## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/content-addressable-hash'>here</a>

## Content Addressable Storage
Content Addressable Storage systems work by passing the content of the file through a [cryptographic hash function](https://en.wikipedia.org/wiki/Cryptographic_hash_function) to generate a unique key, the "content address". The [file system](https://en.wikipedia.org/wiki/File_system)'s [directory](https://en.wikipedia.org/wiki/Directory_(computing)) stores these addresses and a pointer to the physical storage of the content. Because an attempt to store the same file will generate the same key, CAS systems ensure that the files within them are unique, and because changing the file will result in a new key, CAS systems *provide assurance that the file is unchanged*.

In the IPFS ecosystem, this hash is called Content Identifier, or CID.