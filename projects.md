---
layout: default
title: Projects
permalink: /projects/
redirect_from: /projects.html
---

# Experimental Projects 🚧

Here are some of the ongoing and exploratory projects I'm working on:

## Latticework: Mental Models for Architects

A searchable field guide of more than 120 mental models for Solution, Domain and Enterprise Architects, drawing on thinkers such as Martin Fowler, Gregor Hohpe, Eric Evans and Michael Nygard. Each model is rewritten for the decisions architects actually face. Currently in progress, built with help from Claude.

- Technologies: Next.js, React, TypeScript, MDX
- Features: Each model has a one-line summary for executives and one for engineers, a diagram, an example, questions to ask and how it can mislead you. Readers can start from a symptom ("Every decision gets reopened") or a playbook, or explore a map of how the models connect. Includes workshop formats for architecture teams.
- Links: [Visit the site](https://mentalmodels.pothula.me/)

## ArchiWeb

A collaborative, browser-based ArchiMate® 3.2 modelling tool, modelled on [Archi](https://www.archimatetool.com/). It keeps Archi's metamodel, notation, rules and file formats, and adds real-time multi-user editing.

- Technologies: TypeScript, Yjs (CRDTs), SQLite, Git, Model Context Protocol (MCP)
- Features: Live collaboration with presence and per-user undo, Git sync compatible with Archi's coArchi2, views catalog, model health dashboard, `.archimate` and Open Group Exchange import/export
- AI: An MCP server lets assistants such as Claude explore and edit models live, including impact analysis and health checks

## Cadence

A cycling route planner that runs entirely in the browser. Click the map to plan a ride, or let it generate a loop.

- Technologies: JavaScript (no build step), OpenStreetMap, BRouter, Open-Meteo
- Features: Loop generator with difficulty levels, climb detection, elevation profile, surface and road-type breakdown, wind and weather matched to departure time, GPX import/export
- Links: [Try it live](https://pothula.me/cadence/) · [Source on GitHub](https://github.com/kpothula/cadence)

## Kiesraad 2026 🗳️ {#kiesraad-2026}

A web application for browsing Dutch municipal election candidate lists for the 18 March 2026 elections, sourced from official [Kiesraad](https://www.kiesraad.nl/) data. Built with [Lovable](https://lovable.dev/).

- Technologies: React, TypeScript, Vite, Tailwind CSS, shadcn/ui, Recharts
- Features: Search candidates across all municipalities and parties, browse by municipality or party, statistics on candidate demographics and party distribution, Dutch and English, dark mode
- Links: [Visit the site](https://kiesraad2026.pothula.me/)

## Browser-based Policy Q&A Agent

A lightweight Q&A system for internal policy documents, running locally with open-source LLMs and ChromaDB.

- Technologies: ChromaDB, Python, Mini LLM, Ubuntu Server Pro
- Features: Fast querying, private deployment, CI/CD integration

## Architecture-as-Code CI/CD Toolkit

Toolkit to turn architecture practices into programmable, repeatable pipelines.

- Tools: Wardley Maps, Markdown, GitHub Actions
- Goal: Improve architecture traceability and continuous validation

## Local LLM Playground

Experimenting with different open-source LLMs and comparing performance on local machines.

- Focus: Fine-tuning, latency testing, local inferencing

## Interactive Wardley Mapping Interface

A visual editor to create and annotate Wardley Maps with drag-and-drop capabilities.

- Tools: React, D3.js, Mermaid.js
- Goal: Collaborative decision-making and strategic clarity

## AI-augmented Architecture Assistant

A prototype assistant that helps generate architecture diagrams and suggestions based on input requirements.

- Technologies: OpenAI API, Natural Language Processing
- Goal: Bridge the gap between architectural intent and documentation
