# Multi-Agent System Benchmarks

This repository provides an overview of major multi-agent system benchmarks, adapted from the Galileo AI blog post: [Benchmarks and Use Cases for Multi-Agent AI](https://galileo.ai/blog/benchmarks-multi-agent-ai).

## Overview

Multi-agent AI systems leverage collaboration and competition among multiple agents to solve complex problems. Evaluating these systems requires specialized benchmarks that can assess interaction, communication, and coordination.

This repository provides a summary and comparison of the following key benchmarks:

| Benchmark | Focus Area | Advantages | Applicable Scenarios | Limitations |
| :--- | :--- | :--- | :--- | :--- |
| [**MultiAgentBench**](https://arxiv.org/html/2503.01935v1) | LLM-driven multi-agent evaluation | Modular, supports various coordination topologies (star/chain/tree/graph), includes milestone key indicators | Research-to-product transition, reproducible enterprise deployments | May be overly complex for simple applications |
| [**BattleAgentBench**](https://arxiv.org/abs/2408.15971) | Cooperative and competitive capabilities | Seven sub-stages with graded difficulty for fine-grained assessment of cooperation and competition | Market simulation, automated trading, negotiation frameworks | Focuses on language models, lacks evaluation for other agent types |
| [**SOTOPIA-π**](https://arxiv.org/abs/2403.08715) | Social intelligence | Immersive social scenarios to evaluate empathy, social norms, and ethical decision-making | Customer service, healthcare, educational assistants | May not fully measure technical capabilities |
| [**MARL-EVAL**](https://arxiv.org/html/2502.04773v1) | Multi-Agent Reinforcement Learning (MARL) | Statistically rigorous, provides confidence intervals and significance testing; analyzes synergy patterns and specialization development | Robotics, autonomous driving, industrial automation | Primarily for reinforcement learning, does not cover other types |
| [**AgentVerse**](https://arxiv.org/abs/2308.10848) | Diverse interaction paradigms | Rich environments (cooperative tasks, competitive games, creative tasks), supports different architectures and communication protocols | Research teams exploring various architectures | Steeper learning curve |
| [**SmartPlay**](https://arxiv.org/abs/2310.01557) | Strategic reasoning and planning | Uses classic and modern strategy games, focuses on strategic depth, opponent modeling, and adaptability | Financial planning, business intelligence, strategic systems | Game environments may not directly correspond to some domains |
| [**Who&When**](https://arxiv.org/abs/2505.00212) | Failure Attribution in Multi-Agent Systems | Provides a large dataset of failure logs with human annotations, enabling the development and evaluation of automated failure attribution methods. | Debugging and improving the reliability of multi-agent systems. | Focused on failure analysis rather than performance evaluation of successful tasks. |

For a detailed comparison and analysis of each benchmark, please see the following versions:

*   [English Version](Overview_of_Multi-Agent_System_Benchmarks.md)
*   [Chinese Version](多智能体系统基准评测概述.md)
