# BSc_thesis_iaik

Bachelor thesis "Classic McEliece in Rust"

### Abstract
The asymmetric McEliece cryptosystem, although previously unpopular in the cryp-
tographic community due to its large key size, has become an exciting candidate in
post-quantum cryptography because the hardness assumption of the underlying cipher
remains unaffected by quantum computer attacks. In 2016 the NIST (National Institute
of Standards and Technology) initiated the open post-quantum cryptography competition
where the key-encapsulation mechanism classic McEliece is a round 3 candidate. The goal
of this bachelor thesis is to understand the McEliece cryptosystem and port the classic
McEliece implementation from the C programming language to the Rust programming
language. Rust is a language that was developed with the focus on memory safety,
specifically enabling safe low-level memory manipulation while at the same time offering
multi-paradigm language features such as generics, pattern matching, iterators, and many
more. In the course of this thesis, a Rust implementation of classic Mceliece was published
as a crate (library) on the Rust community crate registry. The Rust implementation
yields faster results than the C reference implementation in speed benchmarks.

**Keywords:** Post-quantum cryptography, Rust programming language, code-based
cryptography, Classic McEliece, binary goppa codes


How to build the pdf
----------------

You can use `make` to build `thesis.pdf` and `make clean` to remove temporary files from the build process. 


Requires the packages:
- `latexmk`
- `biber`
- `texlive-binextra`
- `texlive-langgerman`
- `texlive-plaingeneric`
- `texlive-bibtexextra`
