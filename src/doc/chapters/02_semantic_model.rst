2. Semantic model
=================

Distinctions
------------

The following separations are the basis of the proposed requirements:

* Identity continuity does not establish continuity of authority applicability.

* Grant status (for example, not expired or revoked) is distinct from applicability to the particular action and context.

* A valid recorded human decision is distinct from current authority and from whether the decision covers the action now proposed.

* A determination of applicability is distinct from an execution or enforcement outcome.

The first two distinctions build on the author's Theme #5 contribution [R2]. The human-decision distinction and the return-to-operation boundary build on the author's Theme #16 contributions and the UC-6 case [R3–R6].

Decision-relevant context and material change
---------------------------------------------

A decision-relevant context is the set of conditions on which a particular determination depends, as identified by its responsible determining function. Possible conditions include the action, declared purpose, resource or data scope, organizational function, affected party, relying party, environment, relevant state or version, and authority or policy reference. These examples are illustrative, not an obligatory field list.

A material context change occurs when a condition relevant to a prior determination changes in a way that can affect its applicability. A change in declared purpose is material when the applicable grant is purpose-bounded. A change that is irrelevant under the authoritative reference need not cause revalidation. Materiality cannot be established merely by observing that some value has changed, or by accepting an agent's unverified assertion of purpose. Missing or unverified relevant context may leave applicability unresolved.

Context change and late-arriving evidence are related but not identical. In the former, the conditions of the proposed action or reliance point differ from those used in the earlier determination. In the latter, evidence received later may change the assessment of a prior decision, even if the proposed action context has not changed. Theme #33 addresses the latter; coordination is appropriate where both occur.

Reliance and targeted revalidation
----------------------------------

A consuming function relies on an attributed determination only within its established scope. When a material context change is identified, the consuming function shall not infer continued applicability solely from the unchanged source object. It obtains or consumes the necessary updated determination from the responsible function, or represents the inability to establish applicability.

Targeted revalidation means reassessing the affected determination against its decision-relevant conditions. It does not require a universal re-evaluation algorithm, nor imply that other determinations are automatically valid. If dependencies cannot be established, broader reassessment may be necessary under the responsible function's policy.

.. image:: /images/context-revalidation.png
   :alt: Context-bound reliance and targeted revalidation (conceptual interface).
   :width: 100%

Figure 1. Context-bound reliance and targeted revalidation (conceptual interface).

The source decision and any reassessment remain distinct, attributable events. A new determination does not overwrite the historical record. Neither a new context nor a reassessment request constitutes a grant of authority.
