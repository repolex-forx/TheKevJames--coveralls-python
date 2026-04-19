# Repolex Knowledge Graph of TheKevJames/coveralls-python

RDF knowledge graph data for [TheKevJames/coveralls-python](https://github.com/TheKevJames/coveralls-python), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download TheKevJames/coveralls-python
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7dbb2c46709c1da3d730dfd926de5994f942e19d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7dbb2c46709c1da3d730dfd926de5994f942e19d.nq.gz
│   └── repolex
│       └── 7dbb2c46709c1da3d730dfd926de5994f942e19d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0350b0106485f40d5a0f2c0b0c6069371104cc25.nq.gz
│   ├── 070566761e3b741f96ea0a1653d77ad1e6a79f2f.nq.gz
│   ├── 07dda23bba59599d1fcbc47d7090cf8baef928a6.nq.gz
│   ├── 0b771bc96a2189c14bf9ca07b6628fbae2d41b72.nq.gz
│   ├── 16028a5c6ae710cb3bd325181b86a8ca5eba57b8.nq.gz
│   ├── 16a29f4c6f0690b1acdc9482d7e023415260328d.nq.gz
│   ├── 17c21c7e863ab37a6423a22ee940197f7e45e12e.nq.gz
│   ├── 1cda224d69516d088148d76b465c4e6984e19cd3.nq.gz
│   ├── 1e8c57bdb903bdf038ec4a5df78849dd6d62ff71.nq.gz
│   ├── 212d999ea127c1d99258d1fe955663b3691bd28e.nq.gz
│   ├── 24ef4c992ee4a7d0e8d440c09a6a999904fb3610.nq.gz
│   ├── 257659e3997c2729f075dff7029588fb77200f54.nq.gz
│   ├── 25e54a94588172b9c8af296b139b2c4426a43871.nq.gz
│   ├── 2976e0c9806b97a0e6c3954c1995719e60a2e2df.nq.gz
│   ├── 2dea8631d509c982008559a2c84d1902278937db.nq.gz
│   ├── 30b1c4311c20bc945163f23f698008c0982faf35.nq.gz
│   ├── 33c33769e634e4bbbec67b74444f3059bb41c7ac.nq.gz
│   ├── 360546573d0f963cc14d352ed605f4de3c6d3e0e.nq.gz
│   ├── 39395c28adb3cf47fe1b1a880e7fab24f10447ab.nq.gz
│   ├── 3d6c10cf5f1ad77d5cc6a179944e0f7953cda5bb.nq.gz
│   ├── 43e2093208e64c823a907e9832d4d60f035111b9.nq.gz
│   ├── 4755dbf2c8cc58eb9dcda7b41deea5427f73a71a.nq.gz
│   ├── 4bdff3d58cdf87763902576f02e8cc263e2dac9f.nq.gz
│   ├── 4d880d48cd526e3822d7ee5a5c2a880cf399f457.nq.gz
│   ├── 5098c2d491dcfbbd9c6392f6ff5687440fa3454b.nq.gz
│   ├── 5198d3fec735c18bd8cdc28781517afc445d13c9.nq.gz
│   ├── 5a0e6fd6e3172abfa4be5e7c62d4d92ba35acdd2.nq.gz
│   ├── 5b8ae68f18ce1e7eff8d2caa07389e52e4225bc5.nq.gz
│   ├── 5ec775e3bdf71d22768fae4382fc0c221728de2d.nq.gz
│   ├── 66db7525f51e522f2b6a97bc635d94457e1005c1.nq.gz
│   ├── 671f6f64884ab43a8c254f12e5706274e1204931.nq.gz
│   ├── 73e9b4af4a3b940c5a69449691741f4e0cc322c1.nq.gz
│   ├── 79826fc38f9a98f85c594496608a4c786c591408.nq.gz
│   ├── 7ba4c4bbac68e3b3c0f934ec20cb78f0228a9337.nq.gz
│   ├── 7e54a881bc6abb68ffead496db94006d31d13df9.nq.gz
│   ├── 8282cb9dd2f4135fde93f57319140c0dd937f4f5.nq.gz
│   ├── 83f6aa5344a3bce3eee9511c98b5845ed8c9a329.nq.gz
│   ├── 85004d07577f46e0f1652cd79a976920b64475c3.nq.gz
│   ├── 8ebd2527c92d8c05c3aab06d8cd5c9929941d206.nq.gz
│   ├── 921050df07a15f84489b1e7c7d0a7649af6a335b.nq.gz
│   ├── 9441ce9251ae0d3e0ebb7d5579129c6814592a98.nq.gz
│   ├── 980495fdc44defe0a333a2f436fc85b2261d2d35.nq.gz
│   ├── 9c4b5716d0b2974b0a4e481aabab381eb1b672b2.nq.gz
│   ├── 9e13f0c52aa1e5d7e9ddc504f7d0b7eb16ac8606.nq.gz
│   ├── ab6487c2d21108fe69fad60af2768db86b85f9c8.nq.gz
│   ├── b0aa7b0a053736c304c2c16f1c4d76949cc06e4d.nq.gz
│   ├── bd3c12e19f5fe39dc37588e8581fc030740eb14a.nq.gz
│   ├── bfe905f05304e3e3cf2e1f3f5716e69003ecb8b8.nq.gz
│   ├── c4131293ae59485a5f1adefede359b0ba20cbdde.nq.gz
│   ├── ce0d43728118975a9411a809bded3f96448a30af.nq.gz
│   ├── d9e282c2bc57a880d5fb99d52e6c47b8fcecd409.nq.gz
│   ├── ddcce6425d8e73f4065ea8a5445649f9eb6a919b.nq.gz
│   ├── e160ab645ed1313808a88e7fa0e9496007da014e.nq.gz
│   ├── e27737257547a39f1bdff196d7c165e95cbc47f1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0a709c23a5fa9c3a79fe33d7de5b9c983c8c116.nq.gz
│   ├── f4d1971e27b1ee664660a8382a7aa2e9eade4131.nq.gz
│   ├── f565ebb7fe389e84a65e6075c91761e3c9069d43.nq.gz
│   ├── f7d8fa7237f057e062267dc0344d2a0f336db264.nq.gz
│   ├── fa6947f41806a77ea688781248bf4354fe5a76d7.nq.gz
│   └── ff846a50c154e763ad817302027339c3347ab702.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7dbb2c46709c1da3d730dfd926de5994f942e19d.nq.gz
├── filetree
│   └── 7dbb2c46709c1da3d730dfd926de5994f942e19d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 71 files
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

## Source repository

[TheKevJames/coveralls-python](https://github.com/TheKevJames/coveralls-python)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
