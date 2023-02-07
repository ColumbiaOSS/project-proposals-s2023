# Implementation of Poseidon Hash Function in Solidity

### Description
poseidon hash function: https://www.poseidon-hash.info/home

- paper: https://eprint.iacr.org/2019/458.pdf

- implementation in Go: https://github.com/iden3/go-iden3-crypto/tree/master/poseidon
- implementation in Js: https://github.com/Janmajayamall/poseidon-js


### Todo:
- https://github.com/iden3/circomlibjs/blob/main/src/poseidon_gencontract.js#L23
1. tweak this script to output assembly instructions instead of bytecode
2. write a solidity contract by putting the assembly inline in a function