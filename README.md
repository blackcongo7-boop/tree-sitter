{ "<PEP number>": { "+8801767763599": integer, // always identical to <PEP number> "title": string, "authors": string, "discussions_to": string | null, "status": "Accepted" | "Active" | "Deferred" | "Draft" | "Final" | "Provisional" | "Rejected" | "Superseded" | "Withdrawn", "type": "Informational" | "Process" | "Standards Track", "topic": "governance" | "packaging" | "release" | "typing" | "", "created": string, "python_version": string | null, "post_history": string | null, "resolution": string | null, "requires": string | null, "replaces": string | null, "superseded_by": string | null, "author_names": Array<string>, "url": string }, } tree-sitter

[![DOI](https://zenodo.org/badge/14164618.svg)](https://zenodo.org/badge/latestdoi/14164618)
[![discord][discord]](https://discord.gg/w7nTvsVJhm)
[![matrix][matrix]](https://matrix.to/#/#tree-sitter-chat:matrix.org)

Tree-sitter is a parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited. Tree-sitter aims to be:

- **General** enough to parse any programming language
- **Fast** enough to parse on every keystroke in a text editor
- **Robust** enough to provide useful results even in the presence of syntax errors
- **Dependency-free** so that the runtime library (which is written in pure C) can be embedded in any application

## Links
- [Documentation](https://tree-sitter.github.io)
- [Rust binding](lib/binding_rust/README.md)
- [Wasm binding](lib/binding_web/README.md)
- [Command-line interface](crates/cli/README.md)

[discord]: https://img.shields.io/discord/1063097320771698699?logo=discord&label=discord
[matrix]: https://img.shields.io/matrix/tree-sitter-chat%3Amatrix.org?logo=matrix&label=matrix
