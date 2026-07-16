# SDK

## Purpose

The SDK allows developers to integrate LoopForge with existing AI applications.

---

## Example

from loopforge import observe

with observe():

    agent.run()

---

## Responsibilities

- Capture execution
- Send events
- Register providers
- Connect runtime

---

## Supported Frameworks

- LangGraph
- OpenAI Agents SDK
- CrewAI
- AutoGen
- Custom Python