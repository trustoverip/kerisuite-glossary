## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/direct-mode'>here</a>

## Operational mode
To protect a [validator](validator) when engaging with some other controller’s identifier, be it [verification](verification), control authority establishment, or [duplicity](duplicity) detection, are based on an ability to _replay_ the sequence of key events (key event history or log) of that identifier. There are two main operational modes for providing replay capability that are distinguished by the degree of availability of the identifier’s controller when creating and promulgating the key events.  
With direct mode, the promulgation of events to a validator does not happen unless the controller is attached to the network and able to communicate directly with a validator.  
Direct mode assumes that the controller may have intermittent network availability, it also assumes that these mechanism may not be trusted in any persistent sense to promulgate key events. Nonetheless, direct mode is important as it is compatible with the use of mobile internet devices such as cell phones. A single direct mode identifier may be re-used in multiple one-to-one relationships as part of a select group.  
More in [Source: chapter Protocol Operational Modes in KERI white paper](https://github.com/SmithSamuelM/Papers/blob/master/whitepapers/KERI_WP_2.x.web.pdf)

The protocol may operate in two basic modes, called direct and indirect. The availability and consistency attack surfaces are different for the two modes and hence the mitigation properties of the protocol are likewise mode specific.

[Indirect mode](indirect-mode)