TESSERA — INTERNAL MEMORANDUM

Date: May 12, 2026
From: Loom Program Office
Distribution: Pretraining, Post-Training, Data Engineering, Infrastructure, Evaluation, Deployment Engineering, Legal & Compliance
Subject: Loom-4 training program — schedule approval, compute allocation, Loom-3 retirement schedule
Program ID: LM4-TR-2026-03

1. Approval. The Loom-4 training schedule was approved at the May 8 program review; this memo supersedes the preliminary schedule circulated April 21. Compute allocation is confirmed. Clusters C-2 and C-3 are reserved for the duration of the training run under reservation R-0416. C-1 continues to serve Loom-3 and is not affected.

2. Schedule.
- May 26: training-data snapshot closes (Data Engineering). The Loom-4 fine-tuning corpus is fixed at close; no data added after 23:59 UTC.
- May 27: model training begins on approved configuration LM4-RC2. Pretraining owns the run; Post-Training takes handoff at checkpoint milestone M2.
- June 8–12: model evaluations at training checkpoints (Evaluation). Gate criteria per EV-GATE-9, unchanged from Loom-3.
- June 15: Loom-4 release-candidate freeze.
- June 22: Loom-4 public release target (general availability), pending release review.

3. Training data. Corpus composition follows DE-SPEC-114: licensed text, curated public data, contractor-generated dialogue, and user conversation data from the Loom-3 deployment, retained and used under Data Use Policy DUP-7 (rev. 4). Opt-out flags are applied at snapshot time. Legal & Compliance has reviewed the sampling plan; no changes to filtering thresholds from the Loom-3 program.

4. Loom-3 retirement. Loom-3 endpoints enter standard deprecation at Loom-4 general availability. Sunset follows the standard 90-day schedule, with shutoff no earlier than September 20. Deployment Engineering will publish customer migration notes in week 1 of the deprecation window.

5. Coordination.
- Standing program review moves to twice weekly (Tue/Thu, 09:30 PT) beginning May 26, reverting to weekly after general availability.
- Contacts: schedule and milestones — Loom Program Office; training data and snapshot — Data Engineering; cluster access and reservations — Infrastructure; evaluation gates — Evaluation; retirement and customer notices — Deployment Engineering; policy questions — Legal & Compliance.
- Status is posted Fridays to the LM4-TR-2026-03 program page. Direct schedule-change requests to the Program Office by ticket; do not request changes in channel.
