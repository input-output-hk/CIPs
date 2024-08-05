---
CIP: ?
Title: Proposing Changes to Consensus
Status: Proposed
Category: Meta
Authors:
  -  <@iohk.io>
  -  <@iohk.io>
  -  <@iohk.io>
  - Damian Nadales <damian.nadales@iohk.io>
Implementors: N/A
Discussions:
  - <https://github.com/cardano-foundation/CIPs/pull/???>
Created: 2024-08-05
License: CC-BY-4.0
---

## Abstract

## Motivation: why is this CIP necessary?

[Consensus](https://github.com/IntersectMBO/ouroboros-consensus) is one of the components of the [Cardano node][cardano-node].
TODO: should we sumarize the information described [here](https://ouroboros-consensus.cardano.intersectmbo.org/docs/about-ouroboros/)?

We need this CIP to:
<!-- TODO: remove the ones that do not apply, add more if needed -->

- Encourage new collaborators.
- Give guidance for future CIPs that aim at changing Consensus, making it a registered category of the CIP process.
- Give a taxonomy of Consensus changes and prescibe processes for proposing such changes.
- Standardize the process by which Consensus is updated (with new features or fixes).
- Serve as reference to other Cardano node implementations (different from the [de facto one](https://github.com/IntersectMBO/cardano-node)).

## Specification

Aspects we might need to mention:

- When and how new versions of consensus are released. In particular, we might need to summarize and link our release process.
    - Type of releases (eg hard-fork, soft-fork).
    - Examples of when minor or major version bumps are needed.
	- Examples of notable exceptions to our version bumps (eg backports).
- How protocol parameters affect Consensus.
- How are the new versions of Consensus integrated into the node.
- Description of the different types of Consensus changes. Eg
    - Performance improvements.
	- Hotfixes.
	- Bug fixes.
	- New protocols.
- Table matching types of changes to type of releases.

### The Consensus reviewers

The following table gives the current set of reviewers for Consensus CIPs.

| Name | Email | GitHub username |
|------|-------|-----------------|
|      |       |                 |

### Changes that require a CIP

### Processes

All changes that require a CIP SHOULD adhere to the following generic process.

...

## Rationale: how does this CIP achieve its goals?

<!-- TODO: Not sure what we want to write here. The corresponding Plutus and Ledger sections do not seem to answer the question asked in this section header. Aren't the goals of this CIP achieved by having the CIP approved and people following it? -->

## Path to Active

## Copyright

This CIP is licensed under [CC-BY-4.0][].

[CC-BY-4.0]: https://creativecommons.org/licenses/by/4.0/legalcode
[cardano-node]: https://github.com/input-output-hk/cardano-node
