# Current status — 27 September 2026


This is an interim open research companion, not the final manuscript submission.


Completed: development/sensitivity calculations and their numerical replays;
source-video annotation reconstruction; three fixed S01 official hidden-test
results; public EVREN visibility for seven existing model records and both
SeaDronesSee data records. Source-data authorship is explicitly distinguished
from Mehmet AKSOY's adaptation and evaluation work.


Pending: resolution of the three failed D-FINE training jobs and their registered three-export
comparison; five fixed SV01 and six fixed SD01 official-test conditions; complete
portable forward-inference access and cloud worker provenance; integrated final
academic English manuscript and final publication. The 14-condition official
test scope was fixed before the first score; only three have server results.


The historical English v5 draft and inner snapshot status notes have deliberately
not been rewritten under old hashes. Their statements that no official score
or public release existed are historical. This outer status and the included
official-test table document the later completed actions. No new inference,
training or statistical significance is created by packaging.


The local study's successful replays cover six byte-identical annotation files,
81 COCO cells, and 25,665 MRU image-condition decision records. They were executed
in relocated directories on the author's Windows host, not independently by a
second laboratory. The source archive has separate runtime profiles and local
layout assumptions; it is not a universal environment lock or turnkey training
reproduction. Detector weights are linked through EVREN, not redistributed here.


Study conclusions remain limited: H1 selective superiority was not supported;
selection/fusion can trade recall against AP; official train/validation share
known video groups; the new video allocation was designed after development
exposure; S02 is not a verified native YOLO26 comparison. Nothing here establishes
SOTA, a novel detector, an untouched local holdout or a verified cloud GPU model.

## Training incident — 27 September 2026, 12:16–12:17 +03:00

All three D-FINE Small jobs were observed as failed at epochs 42, 42 and 47
of 124 with missing training-image files. A separate membership check found
that one filename requested by the training reader belongs to test in the
retained platform COCO export and to holdout in the frozen local allocation.
This is a filename-level inconsistency: remote image-byte identity and successful
training ingestion have not been established. It does not by itself establish
a corresponding problem in the earlier YOLO worker.

These three jobs are excluded from completed-experiment comparisons until the
effective worker split is resolved. Checkpoint availability alone is not enough
to justify resuming them. A technical report was posted to the EVREN issue board
and verified at 12:29 +03:00. The report requests effective split lists, the
missing-file cause, resume semantics, and optimizer/source provenance. No final
D-FINE result or replacement training is claimed. The 14-condition official-test
scope and the three completed S01 server results remain unchanged.

The forward-inference entry point is still a local development candidate: ten
boundary tests and a relocated import/selector check passed, but its real-image
detector execution has not yet been validated. This does not alter the completed
numerical replays in the existing release. Frozen release assets and their
historical notes are preserved; this status update is a later correction.
