BULLETIN 2026-14

Federated Web Archive Consortium — Replica Integrity Working Group (RIWG)

Date: 19 December 2026

Distribution: Member archives, mirror operators, storage partners. Public.

Supersedes: Bulletin 2026-11 (17 October 2026)

1. Summary

Since the October reporting period, automated integrity sweeps have confirmed 214 cases, across 31 member archives, in which mirrored copies of the same archived text are not byte-identical. In each case both copies carry provenance records that validate against member signing infrastructure. The working group has not identified a mechanism.

2. Character of divergences

2.1. Confirmed divergences are small and textual: single-word substitutions, rephrased or reordered clauses, occasional smoothing of syntax. No case involves deletion of whole passages, insertion of promotional or link content, or visible defacement.

2.2. In 41 of the 214 cases, the divergent copy differs from its counterpart in the direction of greater internal consistency: dates reconciled across a document, citations completed, contradictory phrasings brought into agreement. No member has a submission, patch, or correction request on file corresponding to any of these changes. Operators are reminded that no known corruption mode improves a document.

2.3. A separate, smaller class (9 incidents, 6 archives, November only) consists of crude defacements bearing a repeated signature string. These behave as conventional attacks and are handled under standard incident procedure. Attribution attempts were unsuccessful. The working group does not currently link this class to the divergences in 2.1–2.2.

3. Ruled out

Bit rot (divergences are syntactically coherent); CDN cache divergence (reproduced on cold reads); crawl-pipeline race conditions (affected snapshots predate pipeline changes); compromised operator keys (no anomalous signing activity); automated correction tooling (no member operates any). Affected content shows no commercial, political, or topical pattern. No demand, monetization, or claim of responsibility has been received.

4. Recommendations

4.1. Re-snapshot affected holdings from cold storage where available.

4.2. Enable divergence alerting at mirror level (Appendix A of Bulletin 2026-11).

4.3. Treat archive timestamps as advisory until further notice.

5. Note

Where copies of an affected document disagree, the working group cannot at present state which copy is the original. Members should plan accordingly.
