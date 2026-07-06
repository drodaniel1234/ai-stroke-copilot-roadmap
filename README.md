# AI Stroke Copilot

**Daniel I. Ro, MD** | Vascular Neurologist | Clinical AI Builder

I am building modular clinical AI prototypes that address real workflow pain points in acute stroke care.

## The Clinical Problem

Acute stroke codes are time-sensitive, communication-heavy clinical events. Stroke physicians must track key timestamps, interpret evolving neurologic findings, monitor imaging status, coordinate across multiple teams, document decisions, and manage quality metrics — often while covering multiple simultaneous telestroke or stroke-code cases.

## The Vision

My long-term goal is to build an **AI-powered Stroke Copilot**: a multi-agent orchestration layer that seamlessly manages state across multiple active stroke codes, reduces manual data entry, and provides real-time clinical decision support.

In the future, this orchestration layer could manage case state across multiple simultaneous stroke codes, route information to specialized clinical AI modules, and surface real-time updates such as imaging status, NIHSS findings, treatment eligibility, and quality metrics.

The current projects are intentionally modular. Each demo solves a specific workflow problem today while serving as a building block for a future integrated stroke-code copilot.

## Current Modules

| Module | Clinical Pain Point Solved | Status |
| :--- | :--- | :--- |
| [Stroke-Time-Tracker](https://github.com/drodaniel1234/stroke-time-tracker-v1.3) | Captures key stroke-code workflow times | Early prototype |
| [NIHSS Conversational Assistant](https://github.com/drodaniel1234/NIHSS-Mobile-Assistant-v1.0) | Structures neurologic exam capture | Early prototype |
| [Quality Metric Extractor](https://github.com/drodaniel1234/telestroke-dashboard) | Reduces manual abstraction burden | Early prototype |
| [Telestroke IVT Assistant](https://github.com/drodaniel1234/telestroke-ivt-assistant) | Organizes IV thrombolysis eligibility, contraindications, missing data, and source-text tracing | Early prototype |

## Roadmap

Future modules may include Clinical Reader Mode for transforming cluttered EHR documentation into a standardized clinician-centered reading layer, imaging status monitoring, parallel team communication support, and a multimodal coordination layer that connects clinical agents, workflow data, and physician-facing interaction tools.

The goal is to move from standalone prototypes toward a modular, multi-agent stroke workflow assistant that can support real-time clinical coordination during acute stroke care.

## Safety and Evaluation Framing

These prototypes use synthetic or no-PHI workflows and are not intended for clinical use.

Across the modules, I am exploring evaluation and guardrail patterns such as source-text tracing, missing-data prompts, separation of documented facts from inferred reasoning, hallucination avoidance, and clinician-in-the-loop decision support.

The goal is not to automate physician judgment, but to make high-stakes stroke workflows more structured, auditable, and clinically useful.
