3. Candidate requirements and interface
=======================================

The following candidates consolidate UC-6 requirements 1–6 into cross-function reliance requirements and extend them to prior human decisions and reassessment traceability. They are not asserted as new to FG-TIDA. “Shall” denotes a candidate mandatory property for collective review.

Table 1. Candidate requirements

.. list-table::
   :header-rows: 1
   :widths: 25 75

   * - ID
     - Candidate requirement
   * - CAR-01
     - Context attribution. A determination intended for subsequent reliance shall identify or verifiably reference the responsible function, relevant context, authoritative reference, assessment time and applicable freshness constraints.
   * - CAR-02
     - Applicability separation. A consuming function shall distinguish the status of a source grant or decision from its applicability to the current action and context. Identity continuity or continued source-record existence alone shall not establish applicability.
   * - CAR-03
     - Material-change handling. Where a decision-relevant condition changes materially, the consuming function shall not rely on the previous determination as sufficient for the changed condition without an appropriate reassessment or a responsible function's determination that its scope still covers the action.
   * - CAR-04
     - Responsibility and scope. Revalidation shall address the affected determination through the responsible determining function; a consuming function shall not silently create, extend or substitute authority. Unaffected determinations need not be reassessed solely because an unrelated condition changed, where their independence is established.
   * - CAR-05
     - Human-decision boundary. A recorded human decision shall remain attributable to its reviewed scope. Human approval shall not by itself expand the underlying grant or restore its applicability to a changed context. A distinct, authorized grant modification, where permitted, shall remain separately attributable.
   * - CAR-06
     - Unresolved applicability. When the necessary context, reference or current determination cannot be established, a consuming function shall not treat the absence of a negative result as positive evidence of current applicability. Downstream handling remains subject to the applicable enforcement or oversight requirements.
   * - CAR-07
     - Traceable revalidation. An updated determination shall remain attributable to the original determination, the relevant context and change or reassessment trigger, the responsible determining function, and the resulting outcome; it shall not silently rewrite the historical decision.

Semantic interface
------------------

An interoperable interface need not carry every contextual attribute or reveal sensitive policy content. It should be able to carry, or reference in a verifiable manner, the following information to the extent needed and authorized for the relying function:

* source determination, determining function, assessment time and applicable freshness constraints;

* the relevant reviewed or evaluated action context and applicable authority/policy reference;

* current proposed action context or relevant change reference;

* whether reliance is supported, contextually inapplicable, pending necessary reassessment, or unresolved;

* reassessment result and its attribution, where available.

These are semantic information requirements, not a proposed schema or mandatory new status vocabulary. The final terminology should align with FG-TIDA common terminology and existing authority, verifier and enforcement semantics. In particular, contextual inapplicability is not equivalent to expiry, revocation, missing evidence or a failed execution. The original authority status and the applicability outcome can be represented separately. Privacy-preserving references or selectively disclosed claims may be appropriate; this contribution does not require disclosure of the full grant, internal policy or sensitive context.
