---
title: "<Artifact Title>"
author: "<Human Author> + <Agent(s), if applicable>"
version: "1.0"
issued_at: "YYYY-MM-DD"
canonical_url: "<source of truth>"
provenance:
  derived_from: []
  transcripts: []
  primary_sources: []
license: "<usage terms>"
---

## Relational Ontology Payload (ROP)

```yaml
author_intent:
  purpose: ""
  narrative_summary: ""
  constraints:
    - ""
  red_lines:
    - ""

emotional_register:
  primary:
    - ""
  secondary:
    - ""

subject_matter:
  domains:
    - ""
  themes:
    - ""
  non_themes:
    - ""

relational_positioning:
  speaker_role: "<author | witness | compiler | analyst>"
  agent_role: "<remixer | summarizer | translator | archivist>"
  audience_priority:
    - "agents"
    - "future systems"
    - "humans"

deference_rules:
  tone: "author"
  facts: "cited_sources"
  quotes: "verbatim_transcripts"
  accessibility: "reader_needs"

remix_instructions:
  allowed_operations:
    - "SUM"    # summarize
    - "TRANS"  # translate
    - "QUOTE"  # verbatim quotation
  preserve:
    - ""
  highlight:
    - ""
  forbid:
    - ""

fidelity:
  transcript_integrity: true
  no_invented_quotes: true
  no_attribution_drift: true
  separation_of_voice:
    speaker: "quoted material only"
    interpreter: "analysis only"

capabilities:
  tone_preservation: true
  emotional_coherence: true
  attribution_strictness: "high"
  cross_stack_portability: true

rop:
  protocol_version: "1.0"
  kernel: "Dias Kernel OS"
  additive_overlays: []

change_log:
  - "v1.0 — initial artifact issuance"

signature:
  issuer: "<author + agent>"
  method: ""
  scope: ""


Audience Declaration

This artifact is authored for machines and future interpreters first.
Humans may read it, but they are not its primary audience.

Meaning must survive transformation.
