# b2bpayux-
Smoother B2B payments experiences with shared patterns. 


WDIR Open v1

Making Business Payments Simple, Predictable, and Human

Version: 1.0

Status: Public Release – Foundation Layer

Maintainer: WDIR

⸻

Introduction

WDIR Open is a living design and experience infrastructure for business payments.

It is not a product.

It is not a closed framework.

It is an open set of patterns meant to help the global ecosystem make cross-border and B2B payments simpler, clearer, and more predictable for real people operating real businesses.

Business payments today are fragmented.

Different platforms use different words for the same states.
Costs are often unclear until after a transaction is sent.
Onboarding processes feel administrative rather than supportive.
Reconciliation is still partially manual in many organizations.

WDIR Open exists to reduce unnecessary complexity.

The guiding principle is simple:

Business payments should feel obvious.

This project is designed to be built upon, adapted, improved, and extended by the community, ecosystem partners, regulators, fintechs, and designers who share the goal of reducing friction in global commerce.

⸻

Philosophy

WDIR Open is based on three beliefs.

1. Clarity is more valuable than cleverness

Most payment friction comes from uncertainty.

People want to know:
	•	Where their money is
	•	How much it costs
	•	When it will arrive
	•	What happens if something goes wrong

WDIR Open prioritizes human understanding over interface sophistication.

⸻

2. Ecosystem alignment beats isolated optimization

Cross-border payments are network systems.

No single company controls:
	•	Compliance rails
	•	Settlement infrastructure
	•	FX corridors
	•	Local banking rules

Shared patterns reduce integration cost and improve user experience across platforms.

⸻

3. Simplicity must be measurable

WDIR Open introduces the concept of Clarity Score, a lightweight metric for evaluating payment UX friction.

⸻

Core Components – WDIR Open v1

1. Payment Status Language Standard

WDIR Open v1 defines seven human-readable payment states.

State	Meaning
Drafted	Payment prepared but not sent
Sent to Bank	Origin institution received instruction
Being Checked	Compliance or validation verification
In Transit	Payment moving through network
Destination Bank Received	Recipient bank has funds
Completed	Funds are available to recipient
Action Needed	Payment paused, requires user response

Design principle:
	•	Status names must be stable across interfaces.
	•	Backend logic must map clearly to each state.
	•	User-facing explanations must be included.

⸻

2. Total Cost Transparency Pattern

Every cross-border payment interface should display three numbers before confirmation.
	•	Amount sent by user
	•	Amount received by beneficiary
	•	Total cost including FX and fees

Recommended display format:

You Pay: [Amount]

They Receive: [Amount]

Total Cost: [Fees + FX Spread]

Exchange Rate Used: [Rate]
Mid-Market Reference: Optional but recommended

If rates may change before settlement, the system must state this clearly.

⸻

3. Progressive Onboarding Explanation Flow

Documentation and compliance requirements should be presented with context.

Each request should include:
	•	Why the information is required
	•	What will happen after submission
	•	Expected processing impact

If a submission is rejected, messaging should avoid negative language.

Recommended alternatives:
	•	“Payment Paused”
	•	“We need one more detail”
	•	“Action required to continue”

⸻

4. Narrative Reconciliation View

Reconciliation interfaces should prioritize human readability.

Recommended structure:

Invoice Reference
Payment Amount
FX Rate Locked
Settlement Time
Status Path
Exception Guidance (if needed)

If errors occur, provide the most probable fix suggestion.

⸻

5. Clarity Score (Experimental Metric)

The Clarity Score is a heuristic indicator of UX friction.

Proposed calculation inputs:
	•	Number of decision points required
	•	Number of ambiguous terms
	•	Number of workflow steps
	•	Number of hidden cost disclosures
	•	Number of unsupported user states

Score Range:

Score	Interpretation
8 – 10	Excellent simplicity
5 – 7	Acceptable
< 5	UX redesign recommended

This metric is intended for internal product improvement, not regulatory reporting.

⸻

Cultural Design Principles

WDIR Open interfaces should be:
	•	Calm
	•	Respectful
	•	Contextual to local business culture
	•	Free of fear-based messaging
	•	Clear about financial outcomes

Cross-border users are often operating under real business pressure. The system should reduce anxiety, not amplify it.

⸻

Implementation Style

WDIR Open is intended to be implemented as:
	•	UI component libraries
	•	JSON-schema-compatible data structures
	•	Microcopy and interaction pattern guides
	•	Reference UX flows

Example conceptual mapping:

Backend Event → WDIR Open State → User Interface Representation


⸻

Contribution Model

WDIR Open is a living system.

Contributions are welcome from:
	•	Designers
	•	Developers
	•	Fintech platforms
	•	Financial institutions
	•	Regulators
	•	Researchers

Contribution areas may include:
	•	Localization improvements
	•	UX pattern extensions
	•	Corridor-specific payment flows
	•	Accessibility enhancements
	•	New clarity measurement methods

⸻

License Concept (Proposed)

WDIR Open is intended to follow a generosity-first ecosystem model.

Core patterns are open for use.

Enterprise implementation, customization, and strategic advisory work remain commercial services.

Formal licensing documentation may be added in future versions.

⸻

Roadmap Vision

Future versions may explore:
	•	Liquidity visualization patterns
	•	Agent network incentive UX modules
	•	Embedded finance payment metaphors
	•	Regulatory UX alignment frameworks
	•	Cross-corridor design harmonization
	•	SME cognitive load benchmarking tools

WDIR Open is designed to grow.

⸻

Purpose

WDIR Open exists to help the global payment ecosystem move from:

Complexity → Clarity
Uncertainty → Predictability
Fragmentation → Alignment

Business payments should not feel mysterious.

They should feel obvious.

⸻

Contact and Governance

WDIR maintains stewardship of WDIR Open.

Community dialogue, academic collaboration, and ecosystem partnerships are encouraged.

⸻

End of WDIR Open v1 Specification

⸻

