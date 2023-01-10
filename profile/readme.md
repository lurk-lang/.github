# Welcome to lurk-lang
<p align="center">
  <img width="300" height="300" src="https://user-images.githubusercontent.com/52976094/156452981-7f739d89-14a8-4a10-9071-b805f2fe0c25.svg">
</p>

# Lurk
Lurk is an in-development, Turing-complete programming language for recursive zk-SNARKs.  

## Disclaimer
**DISCLAIMER:** Lurk is an early research-stage language. Neither the cryptography nor the software has been audited, and there is currently no trusted setup for Groth16 circuits. Do not use Lurk in production environments or anywhere else that security is necessary.

## lurk and lurk-rs
[```lurk-rs```](https://github.com/lurk-lang/lurk-rs) is the Rust implementation of Lurk, which generates binaries via ```rustc```. The Rust implementation supports expression evaluation, proof of correct evaluation, and proof verification. ```Lurk-rs``` also provides preliminary support for WASM.

[```lurk```](https://github.com/lurk-lang/lurk) is a Common Lisp reference implementation of Lurk. This implementation only supports expression evaluation. The [language specification](https://github.com/lurk-lang/lurk/blob/master/spec/v0-1.md) lives in this repo, and the implementation provided there aims for simplicity and demonstration of the intended semantics without the proving tools of ```lurk-rs```.

## Features of Lurk
- Lurk program execution can be proved in zero knowledge.
- Lurk proofs support multiple backend SNARK proving systems.
- Lurk enables incremental computation and proofs in unbounded loops.
- Lurk provides conditional control flow.
- Lurk programs are data and vice versa.
- Lurk data is content-addressable for compatibility with IPLD/IPFS.

## Twitter
Follow [@LurkLab](https://twitter.com/LurkLab) on Twitter.

## Website
Visit us on the web at https://lurk-lang.org. 

## License
MIT or Apache 2.0
