---
title: Introduction
---

# AgentScript AI: Build AI Agents That Think in Code

AgentScript AI is an open-source framework for building re-act AI agents that think and plan using code. Instead of relying on traditional step-by-step orchestration, AgentScript AI prompts LLMs to generate code (a subset of JavaScript) that expresses the agent's plan. This code is then executed in a dedicated runtime, providing resumability, state persistence, and interactivity.

## Key Concepts

* **Re-Act Agents:** AgentScript AI is designed for building agents that can reason, plan, and act in a dynamic environment.

* **Code Generation:** LLMs generate JavaScript code to express the agent's plan, allowing for complex logic and decision-making.

* **AST Runtime:** The generated code is parsed into an Abstract Syntax Tree (AST) and executed in a safe, dedicated runtime, not directly in Node.js.

## Why AgentScript AI?

Traditional Re-Act agents often involve a back-and-forth between the LLM and tools, leading to large contexts, slow execution, and inflexibility. AgentScript AI addresses these issues by:

* **Abstract Planning:** LLMs can think more abstractly about the task and express the plan as code.

* **Flexibility:** The code-based approach allows for loops, conditional logic, and complex data manipulation.

* **Efficiency:** Reduced LLM calls and a dedicated runtime lead to faster and more cost-effective execution.

* **Resumability:** Execution can be paused, serialized, and resumed later, enabling human-in-the-loop workflows.

## Installation

Install AgentScript AI using npm:

```bash
npm install agentscript-ai
```