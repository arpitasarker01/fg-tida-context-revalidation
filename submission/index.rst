Context-Bound Authority Applicability and Human Decision Revalidation in Agentic AI
===================================================================================

Candidate technical requirements and assessment cases derived from UC-6

Prepared for consideration  •  First FG-TIDA meeting, Paris  •  30 November–1 December 2026

Abstract
--------

An agentic AI system may retain the same identity, authority grant and technical operation while the purpose or another condition material to the applicability of that grant changes. A recorded human decision may remain valid as a historical decision without authorizing the changed action. Treating the continued existence of these objects as sufficient evidence of current applicability creates a trust-lifecycle interoperability problem.

This contribution proposes a bounded set of implementation-neutral requirements for identifying the context of an existing authority or human-oversight determination, identifying a material change, obtaining reassessment from the responsible function, and preserving the resulting applicability outcome across trust functions. It builds on the controlled FG-TIDA UC-6 purpose-change case, in which the agent, grant, action, documents and requester remain fixed while the declared purpose changes. The proposal complements authority provenance, authorization and privilege management, runtime enforcement, operational human oversight and evidence-driven re-evaluation work; it does not define a new authorization mechanism, policy language or human-confirmation protocol.

This contribution requests review of a bounded requirements and assessment annex derived from UC-6 for integration into the appropriate existing or emerging FG-TIDA workstream. It does not request a separate Working Group or claim adoption of a new deliverable.

History
-------

.. list-table::
   :header-rows: 1
   :widths: 8 38 14 12 28

   * - Version
     - Document
     - Approval
     - Focus Group
     - Working Group
   * - 0.1
     - Proposed technical input, 24 November 2026
     - Not adopted
     - TIDA
     - Allocation pending

Authors
-------

.. list-table::
   :header-rows: 1
   :widths: 25 35 40

   * - Name
     - Affiliation
     - Contact
   * - Arpita Sarker
     - Forkit AI
     - a.sarker@forkit.dev

Keywords
--------

Agentic AI, trust lifecycle, context applicability, authority, human oversight, revalidation, interoperability, UC-6.

Foreword
--------

The ITU-T Focus Group on Trust and Identity for Humans and Agentic AI (FG-TIDA) studies trust management and interoperable identity infrastructure. Its terms of reference recognize the dynamic nature of trust in agentic systems, including behaviour, context, delegation and technical-policy compliance. The present contribution is submitted for technical discussion within that mandate, particularly trust lifecycle and human oversight integration. It is an author-proposed document, not an adopted FG-TIDA deliverable or ITU-T Recommendation.

Note
----

The requirements in this document are candidates for collective review. The work is implementation-neutral; no proprietary product or implementation is required. The UC-6 reference is preserved as a bounded source case. References to proposed themes do not imply their adoption or allocation to a working group.

.. raw:: latex

   \sphinxtableofcontents
   \clearpage
   \pagenumbering{arabic}
   \pagestyle{normal}

.. toctree::
   :maxdepth: 2

   chapters/01_scope
   chapters/02_semantic_model
   chapters/03_requirements
   chapters/04_assessment
   chapters/05_coordination
   chapters/06_references
