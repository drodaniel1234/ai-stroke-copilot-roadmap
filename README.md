# AI Stroke Copilot

**Daniel I. Ro, MD** | Vascular Neurologist | Clinical AI Builder

I am building modular clinical AI prototypes that address real workflow pain points in acute stroke care.

## The Clinical Problem

Acute stroke codes are time-sensitive, communication-heavy clinical events. Stroke physicians must track key timestamps, interpret evolving neurologic findings, monitor imaging status, coordinate across multiple teams, document decisions, and manage quality metrics — often while covering multiple simultaneous telestroke or stroke-code cases.

## The Vision

My long-term vision is an **AI Stroke Copilot**: a workflow-aware orchestration layer that helps organize stroke-code information, support physician decision-making, reduce manual documentation burden, and coordinate updates across the care team.

In the future, this orchestration layer could manage case state across multiple simultaneous stroke codes, route information to specialized clinical AI modules, and surface real-time updates such as imaging status, NIHSS findings, treatment eligibility, and quality metrics.

The current projects are intentionally modular. Each demo solves a specific workflow problem today while serving as a building block for a future integrated stroke-code copilot.

## Current Modules

| Module | Clinical Pain Point Solved | Status |
| :--- | :--- | :--- |
| [Stroke-Time-Tracker](https://github.com/drodaniel1234/stroke-time-tracker-v1.3) | Captures key stroke-code workflow times | Built |
| [NIHSS Conversational Assistant](https://github.com/drodaniel1234/NIHSS-Mobile-Assistant-v1.0) | Structures neurologic exam capture | Built |
| [Quality Metric Extractor](https://github.com/drodaniel1234/telestroke-dashboard) | Reduces manual abstraction burden | Built |
| Thrombolytic Decision Support | Organizes IV thrombolysis eligibility and contraindications | Next |

## Roadmap

Future modules may include imaging status monitoring, parallel team communication support, and a multimodal coordination layer that connects clinical agents, workflow data, and physician-facing interaction tools.

The goal is to move from standalone prototypes toward a modular, multi-agent stroke workflow assistant that can support real-time clinical coordination during acute stroke care.
