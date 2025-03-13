## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/keri-agreement-algorithm-for-control-establishment'>here</a>

#### Acronyms
'KA<sup>2</sup>CE' '[KA2CE](KA2CE)' and 'KAACE'. 

The agreement with KA2CE is as follows:
"... the controller first creates its own receipt of the event and then promulgates the receipted event to witnesses in order to gather their promulgated receipts.  
In this algorithm, an agreement consists of a specific version of an event with verifiable receipts.
(signatures) from the controller and a set of witnesses.  
A state of agreement about a version of an event with respect to a set of witnesses means that each witness in that set has witnessed the same version of that event, and each witness’ receipt in that set has been promulgated to every other witness in that set."  
Source [KERI Whitepaper Section 11.4.2 Agreement](https://github.com/SmithSamuelM/Papers/blob/master/whitepapers/KERI_WP_2.x.web.pdf)

A newly invented algorithm that is a simplification of PBFT class algorithms, separation of control of distributed consensus using distinct promulgation (witness) and confirmation (watcher) networks (new invention), but many non-BFT consensus algorithms do something similar, and one BFT algorithm, Stellar, does something similar but not the same.

What if PBFT and Stellar had a baby missing liveness and total ordering but had safety and were completely decentralized, portable, and permissionless? It would be named KERI.  
(SamMSmith)