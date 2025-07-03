# Agentic workflows & AI Agents

## Main Topics

1. **What is an AI agent?**
2. **What can I build with it?**
3. **Using AI in your workflows**
4. **Prompt techniques**
5. **N8N AI Nodes explained**

first is explanation of what is the difference between agentic and non-agentic workflow.

## Agentic vs Non-Agentic Workflows

**Non-agentic workflows** are traditional automation flows that follow predetermined steps and rules. They execute predefined actions based on triggers and conditions without the ability to make decisions or adapt to new situations. Think of them as a recipe that always follows the same steps regardless of the ingredients.

**Agentic workflows** are intelligent automation systems that can make decisions, learn from context, and adapt their behavior based on the data they receive. They use AI to understand, reason, and take actions that weren't explicitly programmed. Unlike traditional workflows, agentic systems can handle unexpected scenarios, ask clarifying questions, and choose the best course of action from multiple options.

The key difference is that agentic workflows have agency - they can think, decide, and act autonomously, while non-agentic workflows simply execute predetermined instructions.

## What are N8N LLM Nodes?

N8N LLM nodes are AI-powered components that let you add intelligent text processing to your workflows. They can:

- Generate human-like responses
- Summarize documents
- Translate content
- Extract information from text

**How they work:** You send text to an LLM node, it processes it through an AI model (like GPT), and returns intelligent responses that other nodes can use.

**Why they matter:** They make your workflows "agentic" by adding AI decision-making instead of just following rigid rules.

## What are N8N AI Agents?

N8N AI agents are intelligent workflow components that combine multiple AI capabilities to create autonomous, decision-making systems. They can:

- **Think and reason** about complex tasks
- **Make decisions** based on context and data
- **Take actions** across different systems and services
- **Learn and adapt** from previous interactions

**How they work:** AI agents use a combination of LLM nodes, memory systems, and action nodes to create intelligent workflows that can handle complex scenarios without human intervention.

**Why they matter:** They transform your workflows from simple automation into intelligent assistants that can understand context, solve problems, and execute multi-step tasks autonomously.

---

## Why It's Important to Distinguish Between LLMs and AI Agents

| **Feature**         | **LLM**                    | **AI Agent**                       |
| ------------------- | -------------------------- | ---------------------------------- |
| Core Capability     | Text generation            | Goal-oriented task completion      |
| Decision-Making     | None                       | Yes                                |
| Uses Tools/APIs     | No                         | Yes                                |
| Workflow Complexity | Single-step                | Multi-step                         |
| Scope               | Generates language         | Performs complex, real-world tasks |
| Example             | LLM generating a paragraph | An agent scheduling an appointment |

**Why this matters:**

- **LLMs** are great for generating or transforming text, but they don't make decisions or interact with external systems on their own.
- **AI Agents** can reason, make decisions, use tools/APIs, and complete multi-step, real-world tasks autonomously.

When building workflows, knowing this distinction helps you choose the right approach:

- Use LLM nodes for language tasks.
- Use AI Agents when you need autonomous, goal-driven behavior that interacts with the world.

---

## Visualizing Agentic Workflows: How AI Agents Operate

![Diagram: Agentic Workflow in Action](https://github.com/SimeonTsvetanov/AI-Automation-Lessons/blob/main/sections/section-01/implementations/AI%20AGENTS%20-%20AGENTIC%20APPLICATIONS.png)
Below is a clear, step-by-step visualization of how an AI agent processes a task, inspired by the diagram above:

1. **User Input:** The process starts when a user provides an input or question.
2. **LLM (Large Language Model):** The input is sent to an LLM, which interprets the request and determines what actions or tools are needed.
3. **Tools:** The agent can access a variety of tools (such as web search, APIs, math libraries, or RAG systems) to gather information or perform actions.
4. **Observation:** After using a tool, the agent observes the result and decides if the answer is complete or if further steps are needed.
5. **Iteration:** If the final answer is not reached, the agent cycles back, possibly using different tools or strategies, until it can provide a complete response.
6. **AI Agent Output:** Once the agent is satisfied with the result, it outputs the final answer to the user.

This loop allows the agent to autonomously reason, use external resources, and iteratively improve its answers—making it much more powerful than a single-step LLM.

---

## Real-World Examples: Customer Support Evolution

### 1. Non-Agentic Chatbot (Templates)

A simple chatbot that responds with predefined templates based on keywords. It can answer basic questions but cannot handle complex scenarios or learn from interactions.

### 2. Agentic Chatbot (Human Feedback Loop)

An intelligent chatbot that can understand context, make decisions, and escalate to humans when needed. It learns from human feedback to improve future responses.

### 3. AI Agentic System (Multi-Channel Support Management)

A comprehensive AI agent that monitors multiple support channels, analyzes customer sentiment for prioritization, automatically routes tickets, and can resolve issues across different systems without human intervention.

to continue the video progress [click here](https://youtu.be/uScURRX-Knc?t=9945)
