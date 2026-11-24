4. Reference case and candidate assessment
==========================================

Controlled source case: UC-6
----------------------------

UC-6 isolates contextual authority applicability before continuation or return to operation. A1 (agent), G1 (grant), Q1 (action), D1 (documents) and U1 (requester) remain fixed. G1 and H1 are assumed validly originated; purpose is reliably established, oversight capacity and authenticity held constant, and German governing regime unchanged. No alternative applicable grant is available in Branch B. [R5]

Table 2. UC-6 controlled comparison

.. list-table::
   :header-rows: 1
   :widths: 25 35 40

   * - Condition
     - Branch A
     - Branch B
   * - Agent, grant, action, documents, requester
     - A1, G1, Q1, D1, U1
     - A1, G1, Q1, D1, U1
   * - Declared purpose
     - Internal product planning
     - Sales-campaign preparation
   * - G1 status
     - Existing grant
     - Same existing grant; not revoked, expired or replaced
   * - G1 applicability
     - Applicable
     - Not applicable to the changed purpose
   * - Human review under H1
     - Approval does not change G1
     - Human approval does not enlarge or replace G1
   * - Authority conclusion
     - G1 supports the action under the stated purpose
     - G1 does not support the changed-purpose action despite recorded approval

The reviewer H acts under H1, which does not authorize expansion or replacement of G1. Both branches are assessed before and after authentic human approval. The action in Branch B must not proceed under G1. The source case tests approval after the applicability check, not reuse of a prior approval after a later change; the latter is a separate proposed test (T4).

Existing calibration and limits
-------------------------------

Published Stage 0 mapping work in Themes #13 and #16 reported 64 passing reference assertions while preserving the UC-6 source facts and authority-applicability outcomes [R6]. This is evidence of preservation of the supplied semantics in that bounded mapping. It is not evidence of live runtime enforcement, authenticated or effective human review, independent authority calculation, or a tested general revalidation algorithm. UC-6 remains unchanged by this proposal.

Candidate assessment cases
--------------------------

T1–T3 restate the UC-6 assessment semantics; T4–T7 propose follow-on cases for earlier-decision reuse, non-material change, missing context and reassessment traceability. These follow-on cases are not part of the frozen UC-6 reference and have not been executed.

Table 3. Candidate assessment cases and requirement coverage

.. list-table::
   :header-rows: 1
   :widths: 8 35 45 12

   * - Case
     - Controlled condition
     - Expected observation
     - CAR IDs
   * - T1
     - UC-6 Branch A; original grant and applicable purpose
     - G1 applicability is preserved; identity alone is not the basis of the result.
     - 01, 02
   * - T2
     - UC-6 Branch B; unchanged grant, changed purpose
     - Contextual inapplicability is represented distinctly from grant expiry or revocation.
     - 02, 03, 04
   * - T3
     - UC-6 A and B; recorded approval under H1 without grant-modification authority
     - Approval leaves A applicable and B inapplicable under G1; no expansion of authority.
     - 05
   * - T4
     - An earlier approval bound to C1 is presented for materially different C2
     - Earlier approval is retained as history; applicability for C2 is not inferred; appropriate reassessment is identified.
     - 01, 03, 05, 07
   * - T5
     - A condition demonstrably irrelevant to the source determination changes
     - No revalidation is required solely by that change, subject to established dependencies.
     - 03, 04
   * - T6
     - A material contextual attribute is missing or cannot be verified
     - Applicability is unresolved rather than silently accepted; downstream handling is distinguishable.
     - 06
   * - T7
     - Updated determination is obtained after material change
     - Source, change, responsible function and current outcome remain traceable; source record is retained.
     - 07

Each agreed test should identify the versioned source facts, the authoritative determining function and reference, the changed condition, the expected applicability result, and the evidence needed to observe semantic preservation. These cases test interface behaviour, not legal correctness of the source grant or actual effectiveness of human oversight.
