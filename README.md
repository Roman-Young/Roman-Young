## Roman Young

Bioinformatics undergrad at UC San Diego (CS minor, class of 2028).

What I'm working on:

- **[PEPMatch](https://github.com/IEDB/PEPMatch)**: I added indel-aware search to the
  IEDB's peptide-matching tool, in its Rust core. Six PRs merged upstream:
  - [#24](https://github.com/IEDB/PEPMatch/pull/24): 1-indel search via bidirectional DFS in Rust
  - [#27](https://github.com/IEDB/PEPMatch/pull/27): annotate indel hits with edit type and query position
  - [#29](https://github.com/IEDB/PEPMatch/pull/29): honor explicit k, clamp above the pigeonhole optimum
  - [#31](https://github.com/IEDB/PEPMatch/pull/31): 2-indel search + short-query k-partition
  - [#35](https://github.com/IEDB/PEPMatch/pull/35): read metadata only for the proteins a search hits
  - [#36](https://github.com/IEDB/PEPMatch/pull/36): indel DFS walks each side of a seed once, not once per budget split
- **[LabReach](https://labreach.roman-young.dev)**: a RAG system that does the hour of research a
  student would do before cold-emailing a research lab, across 445 labs around UCSD.
- **[Kairo](https://github.com/Roman-Young/agent-machinery)**: a personal AI agent (my son) that
  runs itself on my own server, with a file-based memory it maintains across sessions and a bus
  that fans work out to a fleet of sub-agents.

More at **[roman-young.dev](https://roman-young.dev)**.
