# Repolex Knowledge Graph of console-rs/indicatif

RDF knowledge graph data for [console-rs/indicatif](https://github.com/console-rs/indicatif), parsed by [repolex](https://repolex.ai).

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
lexq download console-rs/indicatif
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4de2f604c3f5af5556db0a1d15e296102879c8d9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4de2f604c3f5af5556db0a1d15e296102879c8d9.nq.gz
│   └── repolex
│       └── 4de2f604c3f5af5556db0a1d15e296102879c8d9
│           └── chunk-001.nq.gz
├── blob
│   ├── 0378f0917718f19008fe3f4df952375b30a6cac6.nq.gz
│   ├── 046ae14a09f1d6ac7933b755b7f316eba298c24a.nq.gz
│   ├── 06a1a2dc34d5b7a752810edd1e3655d5a78d4c3d.nq.gz
│   ├── 0d63561d795916d6922bc9ffc1cd68328f747473.nq.gz
│   ├── 1126a56a873e5cfb91cd6ce2800b9dcf4a6b18c2.nq.gz
│   ├── 129c0f5b6601b46c9837c8947bb65f1970467305.nq.gz
│   ├── 1314c2a429fe12c54c82320ad77dcdc21335e581.nq.gz
│   ├── 17ac2b1fffd4e8de11913cc93a9935f2bb97d5fd.nq.gz
│   ├── 195c9f9d98970feb1d2cb196b0b5d0946284fd2d.nq.gz
│   ├── 197fe0b6b22bdfdee1b76abbcc352ef1bbd1249f.nq.gz
│   ├── 1b71f0ca3acf36305a81404cc9b95d04fcf451db.nq.gz
│   ├── 1e1e17c4634ca56c0c5a5ee8a5ba10449ec97c5d.nq.gz
│   ├── 25e4f13eb11387d5cc428e2f8bd5a5f2ba0351cf.nq.gz
│   ├── 26d506cd00a72615dd86d20457424d58bb55b912.nq.gz
│   ├── 30b664f00d3c45111fd5f9d66ded7b45748fc5ca.nq.gz
│   ├── 354b6e0f62741ea403ca3f479a75e8c4ad2b186c.nq.gz
│   ├── 4a7eb5366b6d7c164c26b81a358073f0da85a2a3.nq.gz
│   ├── 54088d5719e66f10792d30bb8ffb40eed1817dc3.nq.gz
│   ├── 5589ad60dcaff5cfd8d1fa9098687d8a08f9ae1e.nq.gz
│   ├── 61a5990ebf08c1accd51b7ae4c1dcc68368cdb1d.nq.gz
│   ├── 6b145487b86790fde7a1e31ef6f8dde4881f36d9.nq.gz
│   ├── 6e921e54f5c96c0ccaf0052eff8a8a65d942448a.nq.gz
│   ├── 8d03330cf974df9e7089116cd0d74f5f2de1d85e.nq.gz
│   ├── 8ef5278d08df806e702957986e422ab01e54253a.nq.gz
│   ├── 8f4004720b4312bde7d43c90f430c3cad6d91e20.nq.gz
│   ├── 92bac64cc1a11a6c44f659be4dc74e313097d20c.nq.gz
│   ├── 939fa4e67b7aef5de330f6dce0477ec4e3ff7f65.nq.gz
│   ├── ac1f06093ecd1f62b1905684012d2654fd9cbfe3.nq.gz
│   ├── aedf2b67dfb9251be15e74d353dc9ce71533f9f1.nq.gz
│   ├── b489b655dc2b8012428e14625f444df31282e70d.nq.gz
│   ├── b49728086b6ff116f5f1d42d892d30ad9302f681.nq.gz
│   ├── b769f3812307f12300c0d4f2d5073b55f601a294.nq.gz
│   ├── c3f92027a31fbe5904b4d92cabec4a61553eaf5d.nq.gz
│   ├── c6fc18e17e46fa5793d5acd58e9be76ecb23efe1.nq.gz
│   ├── c9a76b6cf446c3422fdb43ceb48585a0f917a13c.nq.gz
│   ├── d8468e0c4fed54f6150675e03f32b483872c7990.nq.gz
│   ├── da5a80fa3afab798e4c9bdca523118a2a8ea816f.nq.gz
│   ├── dc9a85c1ee2f335497ac578f7ff8fced6c49ba6e.nq.gz
│   ├── df58056572074235de6bab721d96769478d48b1a.nq.gz
│   ├── e00d74c4208afbffb3aeda691a33e446ae7a2766.nq.gz
│   ├── e29f7fe7ec6fd09a109a38e07f389615a87d8904.nq.gz
│   └── e4d5b5adbd11691262214f9a8c857575f3ba66d8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 4de2f604c3f5af5556db0a1d15e296102879c8d9.nq.gz
├── filetree
│   └── 4de2f604c3f5af5556db0a1d15e296102879c8d9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 52 files
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

[console-rs/indicatif](https://github.com/console-rs/indicatif)

---
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
