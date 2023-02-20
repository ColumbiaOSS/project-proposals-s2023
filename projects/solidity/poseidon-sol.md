# Implementation of Poseidon Hash Function in Solidity

## Description

poseidon hash function: <https://www.poseidon-hash.info/home>

- paper: <https://eprint.iacr.org/2019/458.pdf>

- implementation in Go: <https://github.com/iden3/go-iden3-crypto/tree/master/poseidon>
- implementation in JS: <https://github.com/iden3/circomlibjs/blob/main/src/poseidon_gencontract.js>
- another implementation in JS: <https://github.com/Janmajayamall/poseidon-js>
- implementation in Python: <https://github.com/ChihChengLiang/misc_crypto/blob/master/misc_crypto/poseidon/hash.py>

## Background

The existing Poseidon hash function implementation for EVM is written in JS, and it is performant but it could be more unreadable. Also, if you write a smart contract in Solidity, it has to link the bytecode or call an external contract address to use poseidon hash, which is inconvenient. In the future, Poseidon hash is likely to be implemented as a precompile contract in the Ethereum protocol (<https://eips.ethereum.org/EIPS/eip-5988>), so that people can call it with cheap gas. However, it would still be valuable to have a reference Poseidon Solidity implementation as a benchmark baseline.

## Todo

- <https://github.com/iden3/circomlibjs/blob/main/src/poseidon_gencontract.js#L23>

1. tweak this script to output assembly instructions instead of bytecode
2. write a solidity contract by putting the assembly inline in a function
3. test that the assembly implementation outputs the same hashes as the regular implementation
