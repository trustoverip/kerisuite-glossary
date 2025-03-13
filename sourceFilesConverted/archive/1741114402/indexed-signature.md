## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/indexed-signature'>here</a>

## Example working
An indexed signature attachment would look something like:
```
03.<binary signature>
```
All encoded as [qualified](qualified) [base64](base64).  A verifier would then know to use the AID’s public key located at index 3 in the list of public keys to verify the signature.  
Source:Philip Feairheller


In addition, [witness](witness) signatures can also be attached as indexed signatures. So a verifier can determine which witness signed a particular [receipt](receipt). This is useful when witnesses are receipting an event and only attaching their own signature. The [controller](controller) knows which witness signed the receipt by looking up the index in their list of witnesses for that event.  
Source:Philip Feairheller


