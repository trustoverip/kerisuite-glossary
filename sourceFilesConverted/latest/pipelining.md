## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/pipelining'>here</a>

## Why CESR needs to anticipate pipelining
If you have a stream coming in, you have to look ahead how big a chunk of data can be. We call this a logical atomic data chunk.

With JSON I don’t know where the end is, so I have to parse the initial stream to find out. That's slow.

That once you have a block of data, that you can pull off chunks and de-multiplex from the stream into cores and multiplex them back into the streams. Cores in big datacenters are now max 5 GHz, a pipeline is 40 GHz. So you have to be able to do pipelining (split off over many cores). [CESR](CESR) is the only streaming protocol that has this anticipation on board.  
Source: Samuel Smith, KERI Zoom meeting Dec 5 2023.

[Multiplexing](multiplexing)
