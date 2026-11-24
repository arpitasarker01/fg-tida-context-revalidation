5. Coordination and proposed work
=================================

Relationship to existing FG-TIDA activity
-----------------------------------------

Table 4. Coordination boundaries

.. list-table::
   :header-rows: 1
   :widths: 25 75

   * - Theme / proposed work
     - Boundary and coordination
   * - #5 — Provenance of authority
     - Addresses authority origination, standing, scope, composition and applicable authority. The proposed requirements preserve and consume its determinations, without a parallel authority model.
   * - #16 — Operational human oversight
     - Addresses the intervention lifecycle, qualified human authority and capacity, evidence, decision and return-to-operation. The contribution supplies a bounded contextual-applicability requirement and assessment input, preserving Matrix v0.2 and D1 v0.1.
   * - #23/#64 — APMA proposal
     - Covers authorization and privilege lifecycle across a task window, including context and reassessment. The contribution does not define privilege grants or transitions; it addresses reliance on prior determinations across the relevant interface, including human decisions that do not modify grants.
   * - #6/#36 — WG2-related runtime verification
     - Determines action-time conformance and enforcement outcomes. This contribution does not define the verdict algorithm or enforcement gate; it addresses scope and current applicability of a prior determination consumed at a reliance point.
   * - #31 — Memory and context handoffs
     - Preserves authority restrictions across transformations. The present contribution addresses changed reliance conditions even when the original record is preserved correctly.
   * - #33 — Non-monotonic eligibility
     - Addresses re-evaluation on late-arriving evidence. The present contribution is limited to changed action/reliance context; a joint case may exercise both triggers.
   * - #57 — Human confirmation
     - Addresses obtaining and recording confirmation. This contribution addresses the applicability of an existing decision rather than the confirmation protocol.
   * - #66 — Conformance test vectors
     - May consume agreed negative and positive vectors if useful. This contribution does not establish a competing protocol test suite.

The problem also relates to attribute- and context-sensitive access control and authorization mechanisms, such as NIST SP 800-162 and OAuth Rich Authorization Requests (RFC 9396). Neither context-sensitive authorization nor reassessment is claimed as new. The proposed value is a bounded cross-function semantic requirement and a source-controlled case that can be reviewed against existing work rather than an alternative architecture.

Proposed output and next steps
------------------------------

The proposed output is a short requirements and assessment annex or section within an appropriate FG-TIDA deliverable: (1) agreed terms and applicability distinctions; (2) candidate requirements refined with the authority and human-oversight source owners; (3) the unchanged UC-6 reference and separately versioned candidate assessment cases; and (4) an explicit interface to the responsible determining functions. A standalone deliverable is not a prerequisite; integration into existing work is preferred if it avoids duplication.

The requirements and assessment cases are intended for review within the relevant FG-TIDA workstream. Subsequent revisions should preserve the versioned UC-6 source facts, distinguish proposed assessments from completed calibration, and maintain traceability to the applicable authority and oversight requirements. Any integration into an existing deliverable is subject to collective review.

Proposed milestones, subject to agreement: Paris (30 November–1 December 2026) — review the scope and coordination boundaries; Geneva (January 2027) — refine the requirements and agree source-case boundaries; subsequent review — agree versioned assessment cases and integrate accepted text into the appropriate deliverable.
