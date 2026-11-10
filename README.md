# Repolex Knowledge Graph of rust-lang/hashbrown

RDF knowledge graph data for [rust-lang/hashbrown](https://github.com/rust-lang/hashbrown), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download rust-lang/hashbrown
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f7bae3d165a3191d086a506ce6a39e516ffd5c67
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f7bae3d165a3191d086a506ce6a39e516ffd5c67
│           └── chunk-001.nq.gz
├── blob
│   ├── 0efc243feb2eed8d4869c6a8610d43c518edd51c.nq.gz
│   ├── 10719990a748a2c68fa4cbd63cfd67bd17566535.nq.gz
│   ├── 13b71bc3e1fbf95ee84e2ca3a0fd718f8bff1bde.nq.gz
│   ├── 145c4292cce7e9a5a655ab53eb0baaffcd4b1e12.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 1a33c5ff308e481923a61df8ecb70774e9b2ed50.nq.gz
│   ├── 20298f40e4c3d6f01094a20a776923969121a755.nq.gz
│   ├── 205d2e0b10042c23bd21e0ab090957266a3a5c8e.nq.gz
│   ├── 26532b84bfd129c34695b53dac742e8c8521060d.nq.gz
│   ├── 27102c228e4abf244723a22e4885ffddb160a5df.nq.gz
│   ├── 2b8fb257ec2164bb59fa6c15ea8098c28a3cb4be.nq.gz
│   ├── 2d92112ee300d4de9f35a3da5f132a2f56b3f2b7.nq.gz
│   ├── 2fa13c128145d49aa80107ce0504eba0ba8a19e7.nq.gz
│   ├── 30865f958a7d8585697fa4587306652ef85127a6.nq.gz
│   ├── 31f0a63e2c07b754566c283765ce4a4446fd462a.nq.gz
│   ├── 3320bfb7b0c2cfcd56835cf47ca83425a7a53f75.nq.gz
│   ├── 402a218201f526d897fbc367500ae81cbff2768a.nq.gz
│   ├── 45009bb0bd9f30ea595c245b8abdbef158e20bc6.nq.gz
│   ├── 463bab3da06bd397769616a618675296c89c5849.nq.gz
│   ├── 47eaf237fd7affb20fded6c1779f05a166a55d91.nq.gz
│   ├── 4d015873bf99764405b9d86c34ca20e649c4d901.nq.gz
│   ├── 59c3eb4c5f2270284e058df31b95af4df91001c0.nq.gz
│   ├── 5afc2a7b0acabd34676023f9ebe3912ea2643ac2.nq.gz
│   ├── 5b591e0c087246861c0040a36974f2bd7b5472f3.nq.gz
│   ├── 61ca69b61d7f26cce6a83f259c836409fa87f85e.nq.gz
│   ├── 62ef8bfcc9bcce48cb0c24d1c78c7519f4f0801a.nq.gz
│   ├── 64f4a41f02f05f576cb49af17fa90313e79a2693.nq.gz
│   ├── 6826688d95761ffa0e2fd7f8ef5f2a7dfe34ad1f.nq.gz
│   ├── 693699042b1a8ccf697636d3cd34b200f3a8278b.nq.gz
│   ├── 7103f68bf9a4953d8d5ed6cb4a20b71024f3d187.nq.gz
│   ├── 72283126cfd5df6f538e6fa379700507ecb457b4.nq.gz
│   ├── 7d93403f23861d337951eaed48bcd452563e6bb2.nq.gz
│   ├── 7ec8aa16dc18932678381bae698b923dd675b183.nq.gz
│   ├── 95c15c18b47ab86cd08dedad8b8a49baa06bb756.nq.gz
│   ├── ac201bf6262d0e4a6bb46e7f2c3bb89c00915872.nq.gz
│   ├── b77f3fc14411efe2e3b6de85967610bb29f523b3.nq.gz
│   ├── b8fb43a37af3b25e8d49ebb27ea4d7bcfee2388a.nq.gz
│   ├── b8fc069d0253188b145dedefe78c8c3acce47ca4.nq.gz
│   ├── bbf680e4f2c7046e4592371c10e8089a1591b40b.nq.gz
│   ├── c1299244225df6967937bdc6463734afbbea7be8.nq.gz
│   ├── c502d780d80152cc9436b000089027d470e77c2c.nq.gz
│   ├── ce19947e4b9cf43874d3cd456e5d5cdcb81486dc.nq.gz
│   ├── ce801273173b4001684c1858df9fdad527a45baa.nq.gz
│   ├── d40fb2c60a891c69cde77b9014066ac622581aa8.nq.gz
│   ├── da7042d77597225af190b7e79e351887ad0e2c23.nq.gz
│   ├── de63570324676139b1dda39dda53c6aa479850e4.nq.gz
│   ├── edf91666b137a544d476b69c9859d24f357f0fbf.nq.gz
│   ├── ef497836cb9895b4e8c98ffd38546164e91000b9.nq.gz
│   ├── f167667b25ed608f2557e0c386d1c2b4c6f35be3.nq.gz
│   ├── f55eee48590202be272bedc2946f7ceba906ea70.nq.gz
│   ├── f5dcba7cc8e5c9f862121a482abe7e1fd162387e.nq.gz
│   └── f97c1a5df4fa25ea7ec9fbfb40a9e1d6dc0d0d73.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f7bae3d165a3191d086a506ce6a39e516ffd5c67.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[rust-lang/hashbrown](https://github.com/rust-lang/hashbrown)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
