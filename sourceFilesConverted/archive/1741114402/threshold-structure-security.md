## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/threshold-structure-security'>here</a>

### In other words
With threshold structures, overall security may be greater than the security of any of the individual parts. 

In [MFA](multi-factor-authentication) the combination of two factors, something you have and something you know, may be much more secure than either of the factors by themselves.

Threshold structures may be employed in a complementary manner to trusted execution environments ([TEE](trusted-execution-environment)) for security. The two types of security are complementary.

This applies to KERI as well. The [witnesses](witness) and [watchers](watcher) independently multiply the attack surfaces of the promulgation and the confirmation networks such that each witness or watcher respectively may be relatively insecure but the system as a whole may be highly secure.

Numerous papers discuss how secure a distributed consensus pool may be. But when comparing *apples* (key management and trusted execution environment (TEE) approach to security) to *oranges* (distributed consensus approach to security) its hard to say that the security of a distributed consensus algorithm is necessarily less secure than the key management infra-structure root-of-trust of any of its nodes. Although as a general rule, in an apples to apples comparison, *more complex is less secure*.

Source: Universal Identifier Theory by Samuel Smith
