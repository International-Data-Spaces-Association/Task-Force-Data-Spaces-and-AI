# Backlog: Data Spaces and AI

> **Status (October 2026):** The position paper *Data Spaces and AI: Trustworthy Agentic Participation in Data Spaces* (Version 1.0, July 2026) is published. Since September 2026 the outcomes below are grouped into four pillars, each run as an interest group. Outcome numbers stay unchanged so that earlier references remain valid.

## Pillars

| Pillar | Focus | First output | Outcomes |
|---|---|---|---|
| 1. Agentic governance and trust | Agent identity, policies, audit and AI regulation | Short note on agent governance, aligned with the Gaia-X compliance work | 3, 4, 7 |
| 2. AI-ready technology and architecture | Connecting AI agents to data spaces, semantics and architecture | Developer guidance on the Model Context Protocol (MCP) and the Dataspace Protocol (DSP); agentic AI input to the Data Spaces Support Centre (DSSC) Blueprint | 1, 2, 5, 6, 8 |
| 3. Use cases, value and outreach | Real cases that show the value of data spaces for AI | Use case catalog (possibly via the Data Spaces Radar) and a one-page value case | 5, 9 |
| 4. Testbed use cases and demonstrations | Use cases and requirements members want to test and demonstrate | 3 to 5 candidate use cases with requirements | 10 |

- **Legal and organizational aspects** (EU AI Act, Data Act, General Data Protection Regulation (GDPR), diverging regional rules for agents acting across data spaces) are covered within Pillar 1 or as a fifth pillar. This is still open.
- **Expanded pillar descriptions** and a questionnaire on the pillars are in preparation. They define tasks and a definition of done for each interest group.
- **A member survey** on activities, needs, concerns and expectations, including expectations for the testbed, runs across all pillars.
- **The testbed** continues in parallel as an interest group with parties from Europe and Asia.

---

## Outcome #1: DSP × AI Protocols Position Paper

How the Dataspace Protocol relates to emerging AI protocols, and why they complement each other.

**Covers:**

- Potential role and function of DSP in UCP, MCP, A2A Agentic Protocols
- A whitepaper on how DSP and MCP will work together, and DCP
- Paper and diagram showing use cases for data space integration with initial set of AI types: RAG, MCP at minimum
- How DCAT, DSP & DCP need to be streamlined to integrate "agent" requests
- Clear and understandable communication how data spaces and AI harmonize
- Explore connections between DSP and MCP, including trust providers
- Communicate DS value alongside MCP: people think DSP is not necessary
- People uninformed about data spaces often think the DSP is not necessary
- With "Better together" positioning
- Distinguish Agentic AI (execution in data spaces) from AI training

## Outcome #2: AI × Data Spaces Reference Architecture

A technical extension of the IDSA Reference Architecture showing where and how AI components fit into a data space.

**Covers:**

- AI Dataspaces Architecture (AIDA) concept development
- A reference architecture including typical data space components (connectors, TSPs, ...)
- Clear architecture of the use of AI with Data Spaces including security aspects of AI modules management
- Report/Reference model of how to integrate data spaces with standard techniques used in AI (VectorDB, GraphDB)
- Integration of AI, specially federated AI, with the Data Space
- Secure management of AI modules and data interactions
- Deepening the Reference Architecture by integrating AI protocols and corporate IT components

## Outcome #3: AI Governance Model & Usage Control Policies

The rules for AI in data spaces: when AI may use data, when not, and how those rules are written and enforced.

**Covers:**

- Governance model for data spaces × AI
- Specific Usage Control Policies to manage AI scenarios
- Recommendations for governance principles and practices, including examples of policies
- Granular usage control distinguishing training / fine-tuning / inference / output reuse
- Definition of clear AI rules in Data Spaces (via Rulebook update or short AI Playbook)
- 3–5 ready-made policy templates (training allowed/not, retention, logging)
- Outputs should feed future versions of the Rulebook
- Model training is a key topic for the media industry, should be covered with more granularity

## Outcome #4: Trust Framework & EU AI Act Alignment

How data spaces deliver trust for AI and help meet regulatory obligations.

**Covers:**

- Trust Framework in AI
- Addressing the EU AI Act
- Oversight and safety of AI Agents interacting with/within data spaces
- Relationship with Trustworthy-AI and XAI
- How can we ensure data sovereignty and controlled data usage in the era of LLMs
- Sector-specific trust sandboxes for cross-border AI
- AI Act compliance: bill of data/software, proofable licence agreements
- Enable trustworthy and reliable use of AI for productive applications
- Rationale why DS is more trustworthy than general AI stacks like MCP
- Trustworthiness as the central value data spaces bring to AI

## Outcome #5: Guidelines & Best Practices for AI–DS Integration

A practical guide for organizations integrating AI into their data spaces.

**Covers:**

- Guidelines / Best Practices for AI-DS Integration: technical aspects, safety and security, AI governance in data spaces, enforcement.
- Requirements and technical specifications for AI data spaces standardisation
- Define clearly the Usage Control Policies of the AI Modules together with the actors involved in training, service providing, and service AI Modules consuming
- Provide outlines on how to properly create an evolving ecosystem to leverage AI from data among multiple participants
- Define responsibility for both AI/Tools and the human users behind AI
- Actionable outputs: standards, governance frameworks, real-world pilots
- Guidance on interoperability, trust, and policy enforcement in AI systems

## Outcome #6: Compute-to-Data & Federated Learning Patterns

Technical patterns for running AI close to the data without moving it across organizational boundaries.

**Covers:**

- Compute-to-data and trusted processing with AI
- How data spaces support federated/distributed machine learning
- Integration of AI, specially federated AI, with the Data Space
- Compute-to-Data and Federated Learning as concrete implementation assets
- How to manage Cybersecurity with AI (Federated Learning) → Trustworthy AI

## Outcome #7: Agentic AI Blueprint

How DSP can be extended to support AI agents with proper identity, accountability, and decision boundaries.

**Covers:**

- Blueprint for how to extend/specify DSP for "agentic" and human decisions
- AI tools and AI agents as participants in a data space, including required interfaces and constraints
- Technical interactions: sequence diagrams showing RAG access, model use, agent↔connector under policy enforcement
- Outline the direction for mechanisms that enable assessment and verification of trustworthiness and reliability of AI agents on data spaces
- ML/AI for DSP/policy resolution/validation

## Outcome #8: Metadata & Catalogue Extensions for AI

How data spaces describe, catalogue, and quality-check AI assets.

**Covers:**

- DCAT-AP: AP schema for all sorts of AI, harmonised with classic ML Meta-Data (MLflow, etc.)
- Clear standards for vectors in catalogue (beyond DCAT, maybe embedded simple json format)
- Metadata definition of AI modules to be integrated into the Data Space Catalogue
- Preparing Data Quality requirements for AI
- Vector-embeddings in the catalogue
- Extending the IDS Information Model to support discovery and semantic interoperability of AI assets — models, datasets, services
- More flexible application profiles harmonized with AI-stack
- Use of PETs linked to AI modules communication
- Impact on standardisation (both AI- and DS-related)

## Outcome #9: Use Cases Collection

A curated catalogue of real-world examples: what works, what doesn't, and what's needed.

**Covers:**

- Examples that really show the impact
- Domain specific current use cases of AI in data spaces
- Use cases and examples of AI and data spaces implementation
- Real-world scenarios and possibilities for data spaces × AI
- List of unsolved use-cases
- A white paper describing recommendations for integration of AI and data spaces with specific use-cases and examples
- Integration of LLMs with source data using Data Space environment

## Outcome #10: International Testbed for AI Data Spaces

- Press Release on the International Testbed
- Definition of certification process for ML/AI training, incl. "bill of data"
- A reference implementation of AI and Data Spaces
- Organization of a conference and social event for TF members
- A list of liaison organizations collaborating to address challenges in AI data spaces
- A whitepaper "Challenges in the Appropriate Use of AI and Data in International Data Spaces"
- Establish partnerships with organizations for conducting research on AI data spaces
