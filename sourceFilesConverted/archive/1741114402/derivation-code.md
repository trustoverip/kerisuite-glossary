## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/derivation-code'>here</a>

### Example
>
> For example suppose that the 44 character Base-64 with trailing pad character for the public key is as follows:
`F5pxRJP6THrUtlDdhh07hJEDKrJxkcR9m5u1xs33bhp=`
>If B is the value of the derivation code then the resultant self-contained string is as follows:
`BF5pxRJP6THrUtlDdhh07hJEDKrJxkcR9m5u1xs33bhp`


All crypto material appears in `KERI` in a fully [qualified](qualified) representation. This includes a derivation code prepended to the crypto-material.
![](https://github.com/WebOfTrust/keri/blob/main/images/derivation-code.png)


![example derivation code in KERI](https://raw.githubusercontent.com/WebOfTrust/WOT-terms/main/static/img/derivation-code.png)


[Key derivation functions](https://en.wikipedia.org/wiki/Key_derivation_function) are not related to the pre-pended derivation codes used in KERI.
