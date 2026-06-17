# Agent roles (illustrative)

These are conceptual agent roles for exploring publishing workflows—not production systems.

| Agent | Role | Named in manuscript? |
|-------|------|----------------------|
| **Literature** | Search, rank, and summarize papers | No — disclose as tool use |
| **Extractor** | Pull structured fields from full text | No — cite pipeline/version |
| **Verifier** | Flag mismatches between summary and source | No — human author accountable |
| **Editor** | Grammar, clarity, condensation | Yes — disclose in methods/acknowledgments |

## On naming agents

Giving an agent a human name (e.g., "Abe") is useful for workflow clarity but does not confer authorship. Names identify roles in a pipeline; authors retain responsibility for claims.

Recommended practice:

1. Use descriptive role names in code and configs (`literature-agent`, not author names).
2. Disclose model, version, and prompts in the manuscript methods.
3. Archive agent configs and outputs as supplementary material when feasible.
