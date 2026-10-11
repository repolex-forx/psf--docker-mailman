# Repolex Knowledge Graph of psf/docker-mailman

RDF knowledge graph data for [psf/docker-mailman](https://github.com/psf/docker-mailman), parsed by [repolex](https://repolex.ai).

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
rlex download psf/docker-mailman
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6b091fc17a578437b320c9ae85bfe50d1a616aef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6b091fc17a578437b320c9ae85bfe50d1a616aef
│           └── chunk-001.nq.gz
├── blob
│   ├── 095f16e882cad33fb2d0b9e76b703fa19788c6ed.nq.gz
│   ├── 1765401d6e959d1129bcc082983135617d3efd74.nq.gz
│   ├── 17e51c385ea382d4f2ef124b7032c1604845622d.nq.gz
│   ├── 1aca307b03dbb5b190879950b20a85c467c71e9d.nq.gz
│   ├── 27d50014fb9a48bef2a733ed0e9e9cf7d434c2f7.nq.gz
│   ├── 2911cfe15d6db365bc8718e2bc25de271064021a.nq.gz
│   ├── 2f5c1f5c18ae31b254f90809b92fdeb89fc490eb.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 3e3c31232cef11c1f58d19333f8629d2662c8807.nq.gz
│   ├── 4e733cf011ca1c48299e44ebd18710ce8acbd7d4.nq.gz
│   ├── 4eb6f348a4764c6267d6dec9d17a60fdb2515faa.nq.gz
│   ├── 50043f6accdee854e9946968770b7320d6d7cd69.nq.gz
│   ├── 519ad2f5b6b6a29d635c697c1a1b2889a71c4a7d.nq.gz
│   ├── 52f6a104f22d6417239f72d9dede09f53491e190.nq.gz
│   ├── 532086873d6f5169d5a84f8c604f8a2ed2cad79d.nq.gz
│   ├── 57566f299a201d3d5e92eb95fc34d67b64ed7b20.nq.gz
│   ├── 6455f0e84f256680a76838e79b4da17010db90a3.nq.gz
│   ├── 6ebf8249d526c132ff826af2362e43824ecfcb57.nq.gz
│   ├── 75fe0c299605dcf4cb5f47e913baa742d22bf0af.nq.gz
│   ├── 78f0cf1e126156f97aadb9c3a836eb8a75ee7325.nq.gz
│   ├── 7a1e5ec4e29ba204056ac93bc9658dbf910eb7e4.nq.gz
│   ├── 7fccfdacdb71eda67fe18cd0dd743565dfde4aa1.nq.gz
│   ├── 8115aecda13a9d700019895633c0b75b8509d3ca.nq.gz
│   ├── 856a7d00dd47c3f08898d4b22ca75431983a84fa.nq.gz
│   ├── 873f4a70156a84ac5ff19409a783235bcaafd044.nq.gz
│   ├── 897ebade79347219c3940e0268e268e29679b159.nq.gz
│   ├── 8e59cd854567a8a2df29f63bb98b22a2018b4992.nq.gz
│   ├── 9868b026593a861d66052db43f0ab4ab6cb132c7.nq.gz
│   ├── ab10f2b228089608a7073ff4ae1e2fc5a92904d0.nq.gz
│   ├── ae50d6c75c06cc9040fd3e40b490766c5d69f713.nq.gz
│   ├── b409cec7780f483910711437f857037169d82f8c.nq.gz
│   ├── b823fa29e898ecfdaba9042c5179fe918d59bef5.nq.gz
│   ├── bc814452954069b9b19fcda726528d8e6f63cb3c.nq.gz
│   ├── c00791f62a4b2448588d11d19b216f12b30f3463.nq.gz
│   ├── c00f015786dbe82c7a256a1295a4b74ad192acb3.nq.gz
│   ├── c1116cf1512b82c9741957e7c167d0dd7d9753db.nq.gz
│   ├── ce9f0de9c0c114faafcf371976738419f0c30b17.nq.gz
│   ├── d0220a6ffc6f0ae89e2df84bd645caf973fc9088.nq.gz
│   ├── d123643aaf150e43d6290c17daa34b26b3a52fab.nq.gz
│   ├── d2366569353c4e367531289697e79a12b266cbdc.nq.gz
│   ├── d3fa4592f91aedecfbdfe72f75f869f5ec6eaa87.nq.gz
│   ├── d4e992c10eaf0797584eb6cd9fb15c2d444b00c4.nq.gz
│   ├── d718be7716c9bbc7a53bdfb873d7899dca19636b.nq.gz
│   ├── e5cd356d8081e9a1d94f0cd67add45892b1558de.nq.gz
│   ├── e5d00a615e158c3e866e88c693f401815e59f915.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec7bdd805b78390a046292903debc3f3cd980e82.nq.gz
│   ├── ee78dfd1b69b37f7695ed4e21876e2e24683284b.nq.gz
│   ├── eeca683c77941bf775288dbedf8e230aa1dc10cb.nq.gz
│   ├── f9726f9e67d10a596ac6efaeb114a6c479fa24ca.nq.gz
│   ├── feb8f08d86dd909d91d3695fac15f19d19c33e22.nq.gz
│   └── ffa459b61e9c4e4e7f30fdf4a12cdf897b647c2e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6b091fc17a578437b320c9ae85bfe50d1a616aef.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 58 files
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

[psf/docker-mailman](https://github.com/psf/docker-mailman)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
