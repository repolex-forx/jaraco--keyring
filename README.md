# Repolex Knowledge Graph of jaraco/keyring

RDF knowledge graph data for [jaraco/keyring](https://github.com/jaraco/keyring), parsed by [repolex](https://repolex.ai).

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
lexq download jaraco/keyring
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 38c040133559682902f25fe96496756ee6849820
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 38c040133559682902f25fe96496756ee6849820.nq.gz
│   └── repolex
│       └── 38c040133559682902f25fe96496756ee6849820
│           └── chunk-001.nq.gz
├── blob
│   ├── 097a9432232c4f916f515b9ac1cf526da78c1484.nq.gz
│   ├── 0d712cabef51b43825e981ac0212e6a945b48cc6.nq.gz
│   ├── 110075b2b3ccc6859d8d6e4282b14e48e4f36aac.nq.gz
│   ├── 11dc6865fed2be9aeb638bbd14becf1c3aacaae9.nq.gz
│   ├── 1248d955ef4ce43dc372f03a96dfb5e89df8a0cf.nq.gz
│   ├── 14243051409fccc0404edd15a2c993e572626dd8.nq.gz
│   ├── 165b5173bca57532827db7cefbea7df630c721ac.nq.gz
│   ├── 18bb6eb0b00350ba8779cbf9aaa9353d4d583a0a.nq.gz
│   ├── 1ffd9ff1fe3d485367b77c70d689f0c52f6d9874.nq.gz
│   ├── 210d6cf6efd2a12ab2b602cf730974b0b028c9e7.nq.gz
│   ├── 2111fa3598060bbecdfbc3662cc153b6245d0ccd.nq.gz
│   ├── 22f1e1c450872bf44fac6534314200606061a61a.nq.gz
│   ├── 2561535c7b4acc9aa061cb64b78a2d559530c5cf.nq.gz
│   ├── 2c0ba4d33526ca5f79655f9d18651cb6c3745a3d.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 3076feda5a41a81f63d9f54047c8f93a75fd843f.nq.gz
│   ├── 41aa78847818835718c995d8adc26d1a65f4b0e2.nq.gz
│   ├── 4f91e16e61169f76332ff176a04e744fa66dca36.nq.gz
│   ├── 5007ab97036d6b604a26f8dac498d2d5a97382f9.nq.gz
│   ├── 53513eee9b3a2f4df50df1febd59a5206718995a.nq.gz
│   ├── 54f99acbfac68c2be8283174ea64f1730a795e49.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5bfae91ff1dd8595a1cde41f55a43f511e3a9590.nq.gz
│   ├── 5dd75f4a8d87d14c513af9ea672418a321ae7843.nq.gz
│   ├── 5fab7addc475c097f386ad30997228b6f97eeed6.nq.gz
│   ├── 63c0825f6bd49615f4f386b95463111f7992f6bc.nq.gz
│   ├── 6a2cecd84e7864b93ff6e028c03c39312eb7f23f.nq.gz
│   ├── 6b4c3b0dd3dc8b557649428f9f33b1eba0c0dfb5.nq.gz
│   ├── 6bc711f1c28f266f1d863730e33c415c04b38613.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 7b0cd393acdbe62384e14853fb8b90d3de917ec4.nq.gz
│   ├── 88a6d108e1a5f72437f406c6c4d45eb24cc56bf3.nq.gz
│   ├── 89a414bfc1b406f5173a428f1b74099fca6afbea.nq.gz
│   ├── 90041582a7e84ebd15cb4ab1216c171a9382ea70.nq.gz
│   ├── 96411f7730979bf08873879f654a22eda04c6533.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── 9fda4df1915b754eb066290a76b29882e59cf636.nq.gz
│   ├── a4bc49c701857430d6156325b2e6adad9b3d6263.nq.gz
│   ├── b108845d0877895e5dc1fa2a519876de8815d258.nq.gz
│   ├── b1d9c8e219155b3543507b24b4deb8a8616c231e.nq.gz
│   ├── b7b02e9fb7fe6dc61cb7a43dcbd8055e3b36b796.nq.gz
│   ├── b8d15e14986aefd646fc4e01bf492cfec38795c1.nq.gz
│   ├── b8ef4c680d7cadc09c4bd2407ceea65931fb4567.nq.gz
│   ├── b92b3c22cdb6c6686fb5467ed3d044a91249802f.nq.gz
│   ├── bfc5cc094c9fe98fa4adb67aba9cb84879390298.nq.gz
│   ├── c3734e29f314a7597e05f8e911f7b19f0a228e60.nq.gz
│   ├── cb5f77c69f595be818e3e66ccfcfc062e4d0aa26.nq.gz
│   ├── d226e149623898a43f35ab57295bb82004dc7d8d.nq.gz
│   ├── d7fadafa23493c51ad0ff4896432ffb6ea703a01.nq.gz
│   ├── d837308a91da768744e99fe119032a2e7d3723db.nq.gz
│   ├── dd4b09d3c7c5624065be7d972b904d70ca9a8197.nq.gz
│   ├── e1ee7a81734585e646bad643d10c17a6b22d5723.nq.gz
│   ├── e39371bbd8f6b786a6b690601fd0f8dc66090876.nq.gz
│   ├── e5cbe70b93da7c56571d4730c2359d1f747fccdc.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7108c073ec95023dac60ba34c1a6318c7737084.nq.gz
│   ├── ea993e158ea8bf3fe4d40b0ac73a5cef02e36716.nq.gz
│   ├── eb29a4b097fd6fd20c6c20d2c6705191529e799f.nq.gz
│   ├── eba76c6b32a5d1627977d7fc0ff320f5a0f06023.nq.gz
│   ├── ed97cf9497704cc672658cb10f47bb95e5b91fc8.nq.gz
│   ├── f0e4670a645690c13e42311610141af9a205cda3.nq.gz
│   ├── f14044ae6f7db38f9ec5c71adb5838a608316de3.nq.gz
│   └── fa5592412f13835ef19d2517513c9f5c4af96ead.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 38c040133559682902f25fe96496756ee6849820.nq.gz
├── filetree
│   └── 38c040133559682902f25fe96496756ee6849820.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 75 files
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

[jaraco/keyring](https://github.com/jaraco/keyring)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
