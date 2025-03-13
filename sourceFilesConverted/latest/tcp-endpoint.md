## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/tcp-endpoint'>here</a>

## More details
Because TCP packets do not include a session identifier, both endpoints identify the session using the client's address and port. Whenever a packet is received, the TCP implementation must perform a lookup on this table to find the destination process.

More on source [Wikipedia](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)