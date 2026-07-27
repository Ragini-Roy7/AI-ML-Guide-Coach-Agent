<div align="center">

# 🤖 AI/ML Guide Coach Agent

### An Adaptive AI Mentor for Machine Learning Education, Interview Preparation, Project Guidance & Career Development

[![Version](https://img.shields.io/badge/Version-v3-success)]()
[![Runtime](https://img.shields.io/badge/Runtime-SmartlyLabs%20Advanced%20V3-blue)]()
[![Status](https://img.shields.io/badge/Status-Deployed-success)]()
[![License](https://img.shields.io/badge/License-MIT-orange)]()

Designed and deployed using the **SmartlyLabs AI Platform**.

</div>

---

# Overview

AI/ML Guide Coach is an adaptive educational AI agent that helps aspiring Machine Learning engineers learn concepts, prepare for interviews, build projects, and receive personalized career guidance.

Unlike traditional chatbots, the agent dynamically identifies the user's intent and routes the conversation into specialized coaching workflows.

The system combines structured prompt engineering, adaptive learning strategies, workflow orchestration, and contextual guidance to deliver personalized educational experiences.

---

# Problem Statement

Learning Machine Learning often involves fragmented resources, inconsistent interview preparation, and generic AI assistants that fail to adapt to the learner's background.

This project addresses those challenges by providing:

- Personalized learning guidance
- AI-powered mock interviews
- Adaptive explanations
- Project mentoring
- Portfolio recommendations
- Career-oriented study plans

---

# Key Features

- Adaptive Learning Mode
- Mock Interview Simulation
- AI/ML Concept Explanations
- Experience-aware Guidance
- Personalized Study Roadmaps
- Project Mentorship
- Portfolio Review Assistance
- Dynamic Follow-up Questions
- Prompt Engineered Responses
- Structured Educational Workflows

---

# System Architecture

<p align="center">

<img src="assets/architecture.png" width="900"/>

</p>

For detailed documentation see:

**docs/architecture.md**

---

# Agent Workflow

<p align="center">

<img src="assets/workflow.png" width="900"/>

</p>

Workflow documentation:

**docs/workflow.md**

---

# Adaptive Decision Pipeline

```text
User Query
      │
      ▼
Intent Classification
      │
      ▼
Mode Selection Engine
      │
      ├──────────────┐
      │              │
      ▼              ▼
Learning        Interview
      │              │
      └──────┬───────┘
             ▼
Prompt Orchestrator
             ▼
SmartlyLabs Runtime
             ▼
Response Evaluation
             ▼
Personalized AI Response
```

---

# Prompt Engineering

The agent uses modular prompt engineering instead of a single static prompt.

Current prompt modules include:

- System Prompt
- Learning Mode
- Interview Mode
- Project Mentor
- Portfolio Guide

Documentation:

**docs/prompt-engineering.md**

---

# Evaluation Strategy

Every response is evaluated against educational quality criteria.

| Metric | Description |
|---------|-------------|
| Relevance | Matches learner intent |
| Technical Accuracy | Correct AI/ML concepts |
| Adaptiveness | Adjusts to learner level |
| Clarity | Beginner-friendly explanations |
| Follow-up Quality | Logical next questions |
| Educational Value | Encourages understanding |

See:

**docs/evaluation.md**

---

# Technology Stack

| Category | Technology |
|-----------|------------|
| AI Runtime | SmartlyLabs Advanced V3 |
| LLM | OpenAI GPT |
| AI Design | Prompt Engineering |
| Workflow | SmartlyLabs Workflow Engine |
| Context | Knowledge Retrieval |
| Versioning | SmartlyLabs Agent Versions |

---

# Repository Structure

```
AI-ML-Guide-Coach-Agent/

├── docs/
├── prompts/
├── assets/
├── examples/
├── research/
├── ROADMAP.md
├── CHANGELOG.md
└── README.md
```

---

# Sample Conversations

Example conversations are available under:

examples/

- Beginner Session
- Interview Session
- Roadmap Session
- Project Guidance

---

# Demo

## Interview Mode

🎥 Demo Video

(Embed screenshot here)

Google Drive:

<Interview Video Link>

---

## Complete Agent Walkthrough

Google Drive Folder

<Folder Link>

---

# Current Capabilities

✅ Adaptive Learning

✅ Interview Simulation

✅ Prompt Orchestration

✅ Personalized Study Plans

✅ Experience Detection

✅ Project Mentorship

---

# Planned Improvements

- Long-term Memory
- Retrieval-Augmented Generation (RAG)
- Vector Database Integration
- Personalized Progress Tracking
- Multi-Agent Collaboration
- Production SaaS Implementation
- REST API Integration
- Dashboard Analytics

---

# Documentation

| Document | Description |
|-----------|-------------|
| Product Overview | docs/product-overview.md |
| Architecture | docs/architecture.md |
| Workflow | docs/workflow.md |
| Prompt Engineering | docs/prompt-engineering.md |
| Evaluation | docs/evaluation.md |
| Design Decisions | docs/design-decisions.md |
| Limitations | docs/limitations.md |
| Future Roadmap | docs/future-roadmap.md |

---

# Future Vision

This repository documents the design and evolution of the AI/ML Guide Coach as an educational AI product.

The long-term goal is to evolve this SmartlyLabs prototype into a production-grade AI coaching platform featuring FastAPI services, Retrieval-Augmented Generation (RAG), vector search, persistent memory, authentication, analytics, and cloud deployment.

---

# License

MIT License












## Future Improvements

- FastAPI backend
- Vector Database
- RAG Pipeline
- LangChain Integration
