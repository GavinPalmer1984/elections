# Deployment

## Status
Proposed

## Context
A person can vote in the elections and be unable to verify that their vote was counted.  One person even ran a verification protocol which proved the election results were not correct.  The verification protocol is to write in a unique name.  Then look up the results to see how many people voted for that unique name write in candidate.

## Decision
Allow people to host their own servers which could connect within a peer to peer network.  The voter needs the option to be the original and final source of truth in an election.

## Consequences
P2P is a decentralized approach which adds complexity, especially when you care about authentic and authorized people using their real identities while non authentic and unauthorized people attempt to undermine the integrity of the process.
