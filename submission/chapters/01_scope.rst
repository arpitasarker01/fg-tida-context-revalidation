1. Scope and problem statement
==============================

Motivation
----------

The same agent may carry out the same technical operation in different contexts. An authority grant permitting document summarization for internal product planning, for example, need not permit the same summarization for sales-campaign preparation. More generally, an organization may apply different authority or oversight conditions to different actions, purposes, organizational functions, data scopes or operating environments. This does not require a universal governance model: the relevant conditions are established by the responsible authority or policy function in each deployment.

The technical problem arises when a trust function relies on a prior determination after one of its material conditions has changed. The identity, grant record, human-decision record or other source artifact may still exist and remain authentic. A relying function must nevertheless distinguish whether the earlier determination still covers the action under consideration. This is a reliance problem, not a proposal to assign authority or to prescribe organizational policy.

Scope
-----

The scope is limited to the semantics and minimum information needed to preserve and reassess the applicability of existing authority and human-oversight determinations when a decision-relevant context changes between the determination and a subsequent reliance point. The reliance point may be an attempted action, continuation or return to operation. The proposed output is a small set of candidate requirements and corresponding assessment cases for integration into existing FG-TIDA work.

The following are out of scope: identity issuance, authority origination or standing, authorization algorithms and privilege state machines, policy expression and conflict adjudication, human-confirmation protocols, human-factors thresholds, enforcement mechanics, legal or organizational governance rules, and generic evidence-driven reopening of past decisions. The contribution does not prescribe a wire format, mandatory context taxonomy, universal risk threshold or universal response to every context change.

Requested decision
------------------

Consider this document as a technical input to the workstream hosting trust lifecycle and operational human oversight (Theme #16), coordinated with provenance of authority (Theme #5), the proposed APMA work (Themes #23/#64), and runtime enforcement. Allocation or integration into another suitable deliverable is welcome. No new Working Group is requested.
