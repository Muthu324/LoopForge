# LoopForge System Architecture

## High-Level Overview

LoopForge is a framework-agnostic runtime for observing, debugging, and operating AI agents in production.

It integrates with existing AI frameworks instead of replacing them.

---

## Architecture

Developer

↓

LangGraph / OpenAI Agents SDK / CrewAI / Custom Agent

↓

LoopForge SDK

↓

LoopForge Runtime

↓

Trace Engine

↓

Storage

↓

Dashboard

---

## Core Components

- SDK
- Runtime
- Trace Engine
- Replay Engine
- Storage
- Dashboard
- Provider Layer
- Plugin System

---

## Design Goals

- Modular
- Framework Agnostic
- Local First
- Production Ready
- Extensible