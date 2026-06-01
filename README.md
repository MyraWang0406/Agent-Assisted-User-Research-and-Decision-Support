# Agent-Assisted User Research and Decision Support

This repository contains a web-based research prototype for exploring how AI agents can support user research, consumer insight analysis, and decision-support workflows.

The system is not intended as a production analytics platform. It is a research prototype for studying how AI-assisted workflows can help users transform fragmented customer signals into more structured, inspectable, and actionable research artifacts.

## Project Information

| Item | Description |
|---|---|
| Status | Research prototype / Work in progress |
| Repository | https://github.com/MyraWang0406/Agent-Assisted-User-Research-and-Decision-Support |
| Live Demo | https://consumer-insight.myrawzm0406.online/ |
| Research Area | Human-AI Collaboration, AI-Assisted User Research, Decision Support, HCI / CSCW |
| Main Methods | LLM-assisted prototyping, agent workflow design, scenario-based analysis, dashboard-based diagnosis |
| Intended Use | Research demonstration, not production deployment |

## Research Motivation

User research and product decision-making often involve fragmented evidence: customer feedback, behavioral data, qualitative observations, A/B test results, lifecycle signals, and customer-service records.

AI systems can generate summaries quickly, but the reasoning process behind those summaries is often opaque. This creates a risk that teams may accept AI-generated insights without inspecting evidence, uncertainty, or alternative explanations.

This prototype explores how AI agents can support user research not only by generating outputs, but by organizing the reasoning process behind those outputs.

## Research Questions

RQ1. How can AI agents help structure fragmented customer and behavioral signals into inspectable user research artifacts?

RQ2. How can agent-assisted workflows support decision-making without hiding uncertainty, evidence gaps, or alternative explanations?

RQ3. How can dashboard-based diagnosis and qualitative research support be combined in one human-centered workflow?

## System Overview

The prototype provides an agent-assisted interface for user research and decision support. It covers several common product and research workflows:

- voice-of-customer analysis
- qualitative research planning
- A/B testing control and interpretation
- lifecycle analysis
- customer-service optimization
- user segmentation
- channel attribution analysis
- dashboard-based diagnosis

The system is designed to help users move from vague business questions to more structured research and decision-support outputs.

## Core Features

- Customer insight monitoring
- Competitive analysis support
- User research planning
- Research-question decomposition
- Customer-service issue diagnosis
- User segmentation support
- Channel attribution analysis
- Dashboard-based decision support

## Example Workflow

1. The user enters a product, customer, or business diagnosis problem.
2. The system decomposes the problem into research and decision-support tasks.
3. Agent modules generate possible research plans, insight categories, or diagnostic directions.
4. The user reviews the outputs and compares possible explanations.
5. The system supports decision-making through structured evidence and dashboard views.

## Research Contribution

This prototype explores how AI agents can support user research as a decision process rather than only a content-generation task.

The contribution is not a new analytics algorithm. The focus is on the interaction workflow:

- how ambiguous questions are decomposed
- how different evidence sources are organized
- how research artifacts are generated
- how users inspect and revise AI-supported interpretations
- how decision-support interfaces can preserve reasoning context

## Relation to Other Prototypes

This project is part of a broader research portfolio on traceable AI-assisted decision-making.

- `UserResearchAgent` focuses more specifically on decision-memory workflows, citation-based reasoning, and evidence-constrained research artifacts.
- `MatrixMirix.WhatIf` focuses on reflective decision-making and role-based what-if reasoning.
- This project focuses on a broader agent-assisted interface for consumer insight, lifecycle analysis, and operational diagnosis.

## Evaluation Plan

This prototype can be evaluated through:

- usefulness of generated research artifacts
- clarity of evidence organization
- perceived support for decision-making
- user trust in AI-assisted diagnosis
- ability to surface uncertainty and alternative explanations
- workload and cognitive load during research planning

## Current Limitations

- The current version is a research prototype, not a production analytics system.
- Some agent behaviors are simplified or simulated.
- The system has not yet been evaluated through a formal user study.
- The dashboard views are intended to demonstrate interaction logic rather than provide complete business intelligence coverage.
- Further work is needed to improve evidence citation, traceability, and comparison across different research outputs.

## Tech Stack

- Frontend: React / Next.js
- Deployment: Cloudflare Pages
- Prototype logic: LLM-assisted / agent-inspired workflow design
- Data: Demo or simulated customer insight scenarios

## License

This repository is for research and portfolio demonstration purposes.
