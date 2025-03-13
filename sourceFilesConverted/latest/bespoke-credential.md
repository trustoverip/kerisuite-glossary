## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/bespoke-credential'>here</a>

## Example
If I want consent terms attached to a presentation of an (set of) ACDC(s).   
Consider a disclosure-specific ACDC, aka tailor made, custom or bespoke. The Issuer is the Discloser, the Issuee is the Disclosee. The rule section includes a context-specific (anti) assimilation clause that limits the use of the information to a single one-time usage purpose, that is for example, admittance to a restaurant. The ACDC includes an edge that references some other ACDC that may for example be a coupon or gift card. The attribute section could include the date and place of admittance.   
For the code of this example, see this [section 11.1 in Github](https://weboftrust.github.io/ietf-acdc/draft-ssmith-acdc.html#section-11.1)

We can use all the tools available for issuance and presentation we already have.

Similar to a presentation exchange, a verifier will first be asked for what they are looking for, secondly the discloser creates the dataset and publishes only the structure and the fields. To accomplish this, thirdly a compact ACDC will be issued (you publish the fields, not the content) and then issuer asks to sign it first. After signing, the disclosee can get the content associated with the on-the-fly contract.

More at [Github source](https://weboftrust.github.io/ietf-acdc/draft-ssmith-acdc.html#name-disclosure-specific-bespoke) 