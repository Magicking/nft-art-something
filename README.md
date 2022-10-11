# NAS

[TEST BADGE]

This document is in work in progress, it shall revisited everytime there is changement in the content of the repository
(eg: update me before git push / commit)

## Idea

NAS is an onchain NFT art project with the goal of leveraging the EVM to produce seekable bytebeat audio stream in an embedded data-URI SVG stream.
It may use an external storage for short programs, like ENS or PUSH, make ringtones for ENS.
As a strech, use NTP and blockchain clock (consensus timestamp instead of block timestamp) to stream synchronized content through speakers using the blockchain.

# Features

 - Create stream (e.g: make WAV file) (P0)
 - Seeking (P1)
 - Synchronized streaming  (P2)

nb: Priority goes in ascending order

# Inputs

 - Short computer programs

# Expected outputs

 - Playable audio stream / file

# Frameworks
 - Solidity
 - [Forge](https://github.com/foundry-rs/foundry)

# References
 - [Updating ENS records](https://docs.ens.domains/dapp-developer-guide/managing-names#updating-other-records)
 - https://arxiv.org/abs/1112.1368
 - https://en.wikipedia.org/wiki/Low-complexity_art
 - https://en.wikipedia.org/wiki/WAV
 - https://www-mmsp.ece.mcgill.ca/Documents/AudioFormats/WAVE/WAVE.html
 - The Bleepmachine https://github.com/wighawag/the-bleep-machine/blob/main/contracts/src/TheBleepMachine.sol
 - https://github.com/ethereum/consensus-specs