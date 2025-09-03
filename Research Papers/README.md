# Research Papers

### 1. MALMM: Multi-Agent Large Language Models for Zero-Shot Robotic Manipulation
MALMM (Multi-Agent Large Language Model for Manipulation) represents the most advanced multi-agent LLM framework specifically designed for robotics. This system distributes planning across three specialized agents: high-level planning, low-level control, and supervisor agents. MALMM addresses key limitations of single-agent approaches by incorporating environment observations after each step, enabling adaptive re-planning and intermediate failure recovery. The framework demonstrates superior performance in RLBench simulations and real-world Franka robot arm experiments.

**Abstract:** Large Language Models (LLMs) have demonstrated remarkable planning abilities across various domains, including robotic manipulation and navigation. While recent work in robotics deploys LLMs for high-level and low-level planning, existing methods often face challenges with failure recovery and suffer from hallucinations in long-horizon tasks. To address these limitations, we propose a novel multi-agent LLM framework, Multi-Agent Large Language Model for Manipulation (MALMM). Notably, MALMM distributes planning across three specialized LLM agents, namely high-level planning agent, low-level control agent, and a supervisor agent. Moreover, by incorporating environment observations after each step, our framework effectively handles intermediate failures and enables adaptive re-planning. Unlike existing methods, MALMM does not rely on pre-trained skill policies or in-context learning examples and generalizes to unseen tasks. In our experiments, MALMM demonstrates excellent performance in solving previously unseen long-horizon manipulation tasks, and outperforms existing zero-shot LLM-based methods in RLBench by a large margin. Experiments with the Franka robot arm further validate our approach in real-world settings.

[MALMM: Multi-Agent Large Language Models for Zero-Shot Robotic Manipulation](https://arxiv.org/html/2411.17636v2)

### 2. Robot Simulation Integration
Robot Simulation Integration
Gazebo and ROS Integration has been extensively explored for LLM-robot control. Recent implementations demonstrate successful natural language control of robots in Gazebo simulations using frameworks like ROSA (Robot Operating System Agent). These systems enable users to issue high-level commands that are translated into ROS control instructions, bridging the gap between natural language understanding and low-level robot control.
[Robot Simulation Integration (MikeLikesRobotics)](https://mikelikesrobots.github.io/blog/llm-robot-control/)



