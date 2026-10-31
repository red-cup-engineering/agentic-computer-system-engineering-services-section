# Capability Marketplace Services Section

This section is a mesh of independently hireable Capability Cells. It is not a
registry with authority over providers, a shared runtime, or a custodian of
customer keys.

## Cell law

- One cell realizes exactly one bounded operation.
- A cell owns its package, repository, wallet, web identity, A2A face,
  ActivityPub actor where publication applies, OCap admission, x402 offer where
  priced border trade applies, append-only record, and deployment.
- Reusable hiring, discovery, authorization, transport, clearing, witnessing,
  and conformance are separate cells. A provider MUST NOT embed a private copy
  of one of those faculties.
- The canonical object is typed RMN with deterministic CBOR identity.
  ActivityStreams, ActivityPub, A2A, OCap/CapTP, x402, RWIL/RDF, and EVM are
  projections or carriers of that same object; none may silently invent a
  second contract identity.
- ActivityPub publishes and federates offers. Offer discovery does not imply
  admission, authorization, payment, execution, acceptance, or completion.
- An OCap authorizes an exact operation, target, predicates, value, chain,
  budget, and expiry. Actor identity alone never grants authority.
- CapTP carries an invocation of an already-authorized object reference. It
  does not discover providers or mint authority.
- A2A carries the task lifecycle. The hire-and-verify cell validates the
  provider Agent Card, required extensions, canonical RMN input/output, and
  exact request/result closure.
- x402 clears a priced HTTP boundary. EVM settlement on `eip155:5615610` closes
  only the nonfactorable payment or commitment residue.
- Every party appends its own receipt through its hired RWIL/RDF provider.

## Reconstruction chain

All experimental marketplace smart accounts and settlement receipts use
`eip155:5615610`. `eip155:561561` is reserved and MUST NOT be used, advertised,
or initialized by this section.

