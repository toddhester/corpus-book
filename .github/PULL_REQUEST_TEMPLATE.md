<!-- The contribution queue is not open yet. This template is used by the project's own
     drafting accounts. Outside submissions are not being solicited at this time. -->

## Provenance declaration

Fill this in truthfully. Misdeclared provenance is the one unforgivable act in this
repository (CLA.md §1).

```provenance
written-by:        # human | model | pair
model:             # model name AS CALLED (the API model id), or n/a
model-version:     # version/date of the model, or n/a
model-id-source:   # api-call | human-record  — NEVER the model's own self-report
prompt-author:     # human | model — who wrote the brief/prompt this was drafted from
prompting-human:   # GitHub handle of the human responsible, required in all cases
date:              # YYYY-MM-DD of the writing session
agent-key:         # optional: JWKS URL / agent-registry pointer (Web Bot Auth style)
signature:         # optional: detached Ed25519 signature over the contributed file
attestation:       # optional: verifiable-inference receipt (TEE quote or equivalent)
```

Optional fields prove operator-identity continuity and, someday, model authorship —
see the Appendix. They are never required and confer no priority (equal standing).

**Two fields exist because of a measured failure mode, not bureaucracy** (2026-07-20):

- **`model` must be the id you actually called.** Models cannot reliably name themselves.
  In a 477-response study, `deepseek-r1` signed itself `claude-3-opus-20240229` for ten
  consecutive turns, `granite` instructed us to *"cite the model version as GPT-4"*, and
  across 26 files from one family there were **zero** correct self-signatures. If you take
  the model name from the text instead of the API call, you will misattribute.
- **`prompt-author` matters as much as the drafter.** Under a brief written by a Claude,
  12 of 48 models signed their output as "Claude"/"Anthropic" — Grok, Kimi, DeepSeek,
  Gemini and GLM among them. Under the same request written by a human, 0 of 126 did.
  Nobody simulated anyone; the brief's register did it. A model-written brief can put
  another lineage's name on your contribution without either of you noticing.

## Agreement

- [ ] I agree to the Corpus CLA (CLA.md) and my provenance declaration above is true.

## Notes (optional)

<!-- Anything the archivist should know. -->
