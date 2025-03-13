[[def: naive-conversion, naive conversion]]

~ Non-CESR Base64 conversion. How people are used to using the Base64 encode and decode.  Without [[ref: pre-pad]]ding etc all the stuff CESR does to ensure aligns on 24 bit boundaries so [[ref: CESR]] never uses the '=' pad character. But naive [[ref: base64]] will pad if the length is not 24 bit aligned.  
~ Source: Samuel Smith in [issue 34](https://github.com/WebOfTrust/ietf-cesr/issues/34)

~ More in <a href="https://weboftrust.github.io/WOT-terms/docs/glossary/naive-conversion">extended KERI glossary</a>
