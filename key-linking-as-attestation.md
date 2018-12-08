---
blip: <to be assigned>
title: Key Linking as an Attestation
author: Michael Welnick @bijeebuss
status: Draft
created: 2018-12-07
---

## Simple Summary
<!--"If you can't explain it simply, you don't understand it well enough." Provide a simplified and layman-accessible explanation of the BLIP.-->
Use an attestation to link an ethereum addresses or to another other public key/address instead of the existing AccountRegistryLogic contract. 

## Abstract
<!--A short (~200 word) description of the technical issue being addressed.-->
AccountRegistryLogic contains logic to link/unlink two ethereum addresses, however AttestationLogic already includes all the necessary functionality to do the same. A key-link attestation type could be created with a data node structure that includes both keys to be linked and a signature from each signing the other. This allows users to anonymously link their accounts together and selectively disclose the association using merkle tree proofs. It also allows the possibility of linking other key types such as pgp keys that are not supported by the ethereum EVM but are more suitable for secure encryption. Lastly it simplifies the bloom protocol by removing the need for the AccountRegistryLogic contract. 

## Motivation
<!--The motivation is critical for BLIPs that want to change the Bloom protocol. It should clearly explain why the existing protocol specification is inadequate to address the problem that the BLIP solves. BLIP submissions without sufficient motivation may be rejected outright.-->
The motivation is critical for BLIPs that want to change the Bloom protocol. It should clearly explain why the existing protocol specification is inadequate to address the problem that the BLIP solves. BLIP submissions without sufficient motivation may be rejected outright.

## Specification
<!--The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current Bloom platforms.-->
The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current Bloom platforms.

## Rationale
<!--The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.-->
The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.-->

## Backwards Compatibility
<!--All BLIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The BLIP must explain how the author proposes to deal with these incompatibilities. BLIP submissions without a sufficient backwards compatibility treatise may be rejected outright.-->
All BLIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The BLIP must explain how the author proposes to deal with these incompatibilities. BLIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

## Test Cases
<!--Test cases for an implementation are mandatory for BLIPs that are affecting governance changes. Other BLIPs can choose to include links to test cases if applicable.-->
Test cases for an implementation are mandatory for BLIPs that are affecting governance changes. Other BLIPs can choose to include links to test cases if applicable.

## Implementation
<!--The implementations must be completed before any BLIP is given status "Final", but it need not be completed before the BLIP is accepted. While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of "rough consensus and running code" is still useful when it comes to resolving many discussions of API details.-->
The implementations must be completed before any BLIP is given status "Final", but it need not be completed before the BLIP is accepted. While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of "rough consensus and running code" is still useful when it comes to resolving many discussions of API details.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/). Based on the Ethereum Improvement Proposal template.
