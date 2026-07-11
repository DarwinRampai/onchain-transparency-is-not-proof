# A Transaction Is Not Its Authorization Chain

A transaction can be real, successful, and independently reproducible while
still failing to prove the authority claimed for it.

In a bounded review of 17 Aave configuration actions, seven actions linked
through executed governance proposals, payload targets, an authorized executor,
execution transactions, and resulting configuration changes. Ten actions used
delegated steward or automation paths.

For those ten delegated paths:

- immediate execution mechanics were explained for nine;
- originating authorization was established for two;
- originating authorization remained Partial for seven; and
- one path remained authority-Unknown.

Nothing in those results establishes misconduct. It establishes a proof
boundary:

```text
execution != registration != administration != role grant != governance mandate
```

The transaction proves execution. A governance conclusion requires the rest of
the evidence chain.

Read *Onchain Transparency Is Not Proof*:  
https://doi.org/10.5281/zenodo.21307247

Public evidence record:  
https://github.com/DarwinRampai/onchain-transparency-is-not-proof
