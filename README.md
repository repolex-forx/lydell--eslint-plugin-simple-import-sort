# Repolex Knowledge Graph of lydell/eslint-plugin-simple-import-sort

RDF knowledge graph data for [lydell/eslint-plugin-simple-import-sort](https://github.com/lydell/eslint-plugin-simple-import-sort), parsed by [repolex](https://repolex.ai).

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
lexq download lydell/eslint-plugin-simple-import-sort
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 90078e7fce900b6860ab7cd1800c6ff055601d88
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 90078e7fce900b6860ab7cd1800c6ff055601d88.nq.gz
│   └── repolex
│       └── 90078e7fce900b6860ab7cd1800c6ff055601d88
│           └── chunk-001.nq.gz
├── blob
│   ├── 0341d604fa8b8b5c12db865d131e7e87f25cdb61.nq.gz
│   ├── 03b75429295457e3676c616c8f4686f275d19d3c.nq.gz
│   ├── 0413b034d526bf01b264da02b2962072857a66ac.nq.gz
│   ├── 08567482ed0bf265ef3bee3ec1f067bd683d6f60.nq.gz
│   ├── 16d804969171cc13a20013e6cf1e2884fb1a2cbf.nq.gz
│   ├── 184b659280c9d5f93634ce6b95c9bd2b53c05e34.nq.gz
│   ├── 1cdc60fada0d24a7f57b6eff76f771ca9441c822.nq.gz
│   ├── 21635981da8711257499506d2e2e3df633b393b5.nq.gz
│   ├── 26da6405c7e31782df7e168ecd737d3814dafc2c.nq.gz
│   ├── 37355c837c22800675d8b7aeb06b7d9c5b8567c7.nq.gz
│   ├── 44df29bbba9d3f8af09d7140217d736d01dd75e3.nq.gz
│   ├── 4bc117fec43359120fc727b6cc51098f52373338.nq.gz
│   ├── 54bc956c833e30e724d77228c8761ea9e3371001.nq.gz
│   ├── 5d8910af3f36a0cda2c029cc8c9f6ae258fa6b7c.nq.gz
│   ├── 61ee6aea2c16662378d2842abed5d97835fdfb30.nq.gz
│   ├── 67a3701c1fdc3f94b0fbe97a5dc75c573c3c62c4.nq.gz
│   ├── 68a0c6cc4e1a2dcc072c3cb06a082dcc23b8bb40.nq.gz
│   ├── 6abfbfc3e321b9e1c84dfcc53cb83b42046d27bf.nq.gz
│   ├── 6caf46f3016359c7006fce2d2145fa65972213af.nq.gz
│   ├── 6fe4028e7839f4b9d4cd85a2fc811eece3cc3bcf.nq.gz
│   ├── 7503dc8410b280811bc45dd4d7fb56422d9dd0e7.nq.gz
│   ├── 75f83fa5f132853a22add725269c534214ee64ef.nq.gz
│   ├── 7660b81a1bfcce025f65fb857f390531f83c40f8.nq.gz
│   ├── 7c881a647e1b713bb1ce3f82f75cfd78652116dd.nq.gz
│   ├── 818d77ab3defc136cf81571379d4102ce11d137b.nq.gz
│   ├── 8286573c26080b35f1842be29e71c9551794df8f.nq.gz
│   ├── 8a27f44f14d8138b23449fcebecc0dc21424cca3.nq.gz
│   ├── 9a4a159b0e1bdca983917c4df9349a9db4f0dd9a.nq.gz
│   ├── 9c1946b92c86285a345ef8d69dcdbd5f3b611114.nq.gz
│   ├── 9c8ff32e1217465a99ebe033cb0fe20c7c354e05.nq.gz
│   ├── 9dd6dd600375b61e6237af69490154302dfdbf75.nq.gz
│   ├── a079d265eb4da4a73d0dbf440ae1d03b2d65a741.nq.gz
│   ├── b0c871eadd9b3c933185fdc87db3b7e80eed2bf0.nq.gz
│   ├── b9ff65d06f438d549e5d4a423d30a78df6b08c35.nq.gz
│   ├── c29336c656d0bcfe74d765f435f104f56b5a651a.nq.gz
│   ├── c810c8e81dd996c3cdbc72e6a05d5f51fab065df.nq.gz
│   ├── d2504b43d500a65dc58664ecc276978f04261363.nq.gz
│   ├── d29064db581eaa4729e8353e2fb76ddc9242d67e.nq.gz
│   ├── d5e5b063713974ce45b8e97fd7c6516c08946ff3.nq.gz
│   ├── d91c56fa4be4b9f1c3aa301f60ceead5f7386956.nq.gz
│   ├── e0ae0923e1f6210338baea1268825c0a7246efc2.nq.gz
│   ├── e54bb563cdd51a812cc0404dd1d264c4553217aa.nq.gz
│   ├── ea878507d60073460e5697a8e257391bef55711b.nq.gz
│   ├── f0610004048bbed9e96b980aed138c695857e944.nq.gz
│   ├── f196d2a04ae5fa02c5aba698e5381f5b108d29a0.nq.gz
│   ├── f5e9c7341c3269776ce2a345deb935b7542bc17a.nq.gz
│   ├── f799e1f863bda871801af92500e4c83b1c5795b7.nq.gz
│   ├── f891c04892aa4da516894b86cbf46facb9eb68c7.nq.gz
│   ├── fdb9c78aab270350fdcea993f8ca19c1f8f63edc.nq.gz
│   └── ff272c386184225928ee691242613984f010c351.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 90078e7fce900b6860ab7cd1800c6ff055601d88.nq.gz
├── filetree
│   └── 90078e7fce900b6860ab7cd1800c6ff055601d88.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 60 files
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

[lydell/eslint-plugin-simple-import-sort](https://github.com/lydell/eslint-plugin-simple-import-sort)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
