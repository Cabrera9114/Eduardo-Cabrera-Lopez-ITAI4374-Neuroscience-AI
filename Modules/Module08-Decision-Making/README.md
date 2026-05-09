# Module 08 – Decision Making and Autonomous Systems

## Overview

This module explored how biological brains and artificial intelligence systems make decisions under uncertainty.

The coursework connected:
- neuroscience
- reinforcement learning
- autonomous systems
- AI agents
- cognitive psychology
- decision architectures
- reward systems
- planning systems
- System 1 vs System 2 reasoning

The module examined how the brain transitions from:
- sensing
- memory
- attention
- into action selection and decision execution.

The course also explored how modern AI systems replicate many of these biological processes using:
- reinforcement learning
- actor-critic systems
- planning agents
- chain-of-thought reasoning
- autonomous agent loops
- Monte Carlo Tree Search
- confidence thresholds
- self-correction systems

---

## Topics Covered

- Decision neuroscience
- Prefrontal cortex
- Basal ganglia
- Amygdala
- Anterior cingulate cortex
- Working memory
- Emotional integration
- Value scoring
- Reward systems
- Somatic marker hypothesis
- Iowa Gambling Task
- Actor-critic architecture
- Go / No-Go pathways
- Dopamine systems
- Reward prediction error
- Drift Diffusion Model
- Speed vs accuracy tradeoff
- Perceptual decisions
- Value-based decisions
- Social decisions
- Theory of mind
- Cognitive biases
- Anchoring bias
- Loss aversion
- Confirmation bias
- Reinforcement learning
- Temporal difference learning
- AlphaGo
- Monte Carlo Tree Search
- Chain-of-thought reasoning
- Tree of Thoughts
- Autonomous AI agents
- System 1 vs System 2 reasoning
- Agent loops
- AI alignment
- AI safety

---

## Files Included

### Module Resources
- ITAI_4374_Module_08_Decision_Making_Brain_Systems.pdf
- ITAI_4374_Module_08_Decision_Making_Brain_and_Autonomous_Systems.pdf
- ITAI_4374_Module_08_Decision_Making_Brain_and_Autonomous_Systems.pptx

---

## Key Concepts Learned

This module focused on how the brain chooses what to do after processing information from sensation, memory, and attention systems. The coursework explained that decision-making is fundamentally a process of selecting one action while suppressing competing alternatives under uncertainty. :contentReference[oaicite:1]{index=1}

One of the most important insights from this module was that biological decision systems and AI decision systems solve many of the same computational problems.

---

## The Brain’s Decision System

The module explained that decision-making is not controlled by a single brain region. Instead, multiple interconnected systems work together in parallel. :contentReference[oaicite:2]{index=2}

The four major regions discussed were:

### Prefrontal Cortex
Responsible for:
- planning
- working memory
- reasoning
- goal management
- value comparison

Subdivisions included:
- dlPFC
- vmPFC
- orbitofrontal cortex (OFC)

:contentReference[oaicite:3]{index=3}

### Basal Ganglia
Responsible for:
- action selection
- suppressing competing actions
- reinforcement learning behavior

The module explained the:
- Go pathway
- No-Go pathway
- dopamine modulation system

:contentReference[oaicite:4]{index=4}

### Amygdala
Responsible for:
- emotional significance
- risk evaluation
- threat assessment
- emotional weighting

The coursework demonstrated how emotions contribute to decision quality rather than simply interfering with reasoning. :contentReference[oaicite:5]{index=5}

### Anterior Cingulate Cortex (ACC)
Responsible for:
- conflict monitoring
- error detection
- effort signaling
- uncertainty management

:contentReference[oaicite:6]{index=6}

---

## Somatic Marker Hypothesis

One of the most fascinating topics was Antonio Damasio’s Somatic Marker Hypothesis.

The coursework explained that:
- emotional body signals influence decision-making
- past experiences generate subconscious warning signals
- humans often react emotionally before conscious reasoning catches up

The Iowa Gambling Task demonstrated that healthy participants avoided risky choices before they could consciously explain why. :contentReference[oaicite:7]{index=7}

The module emphasized that:
- emotion is not the enemy of rationality
- emotion is essential for effective real-world decision-making

This also highlighted a major limitation of current AI systems:
AI systems do not truly feel:
- risk
- danger
- fairness
- trust
- obligation
- emotional weight

---

## Go / No-Go Decision Architecture

The module explored how the basal ganglia regulate action release using competing systems.

### Go Pathway
- releases selected actions
- enables movement and commitment

### No-Go Pathway
- suppresses competing actions
- prevents impulsive behavior

Dopamine dynamically adjusts the balance between these systems. :contentReference[oaicite:8]{index=8}

This concept was directly connected to:
- reinforcement learning
- actor-critic systems
- policy selection
- Q-learning

---

## Three Types of Decisions

The coursework explained that different decisions rely on different neural circuits.

### Perceptual Decisions
Examples:
- identifying objects
- detecting signals
- classification tasks

AI parallel:
- computer vision
- image classification
- object detection

### Value-Based Decisions
Examples:
- choosing between rewards
- comparing costs and benefits
- preference estimation

AI parallel:
- recommendation systems
- ranking systems
- reinforcement learning

### Social Decisions
Examples:
- trust
- fairness
- punishment
- cooperation
- negotiation

AI parallel:
- language models
- multi-agent systems
- social AI

:contentReference[oaicite:9]{index=9}

---

## Drift Diffusion Model

The module introduced the Drift Diffusion Model (DDM), which explains how the brain accumulates evidence before committing to a decision. :contentReference[oaicite:10]{index=10}

The DDM included:
- drift
- noise
- thresholds
- evidence accumulation

The coursework demonstrated that:
- fast decisions increase errors
- slower decisions improve accuracy
- thresholds change based on context and risk

This concept strongly resembled:
- AI confidence thresholds
- classifier confidence scoring
- Bayesian inference
- probabilistic reasoning systems

---

## Speed vs Accuracy Tradeoff

One of the major themes of the module was that every decision system must balance:
- speed
- accuracy

The brain dynamically changes thresholds depending on:
- stakes
- danger
- uncertainty
- familiarity

:contentReference[oaicite:11]{index=11}

The module connected this to AI systems such as:
- autonomous vehicles
- medical diagnosis systems
- trading algorithms
- autonomous robotics

---

## Dopamine and Reward Prediction Error

The module explained that dopamine is not simply a pleasure chemical. Instead, dopamine acts as a teaching signal that encodes reward prediction error. :contentReference[oaicite:12]{index=12}

Three scenarios were explored:
- better than expected outcomes
- expected outcomes
- worse than expected outcomes

This directly connected to:
- temporal difference learning
- reinforcement learning
- Q-learning
- policy optimization

The module explained that neuroscience later discovered dopamine systems compute signals extremely similar to reinforcement learning TD error functions.

This was one of the strongest neuroscience-to-AI parallels in the entire course.

---

## Exploration vs Exploitation

The coursework explored the balance between:
- exploiting known successful strategies
- exploring new possibilities

Examples included:
- epsilon-greedy strategies
- UCB
- Thompson sampling

:contentReference[oaicite:13]{index=13}

The module explained that:
- dopamine supports novelty seeking
- habits support exploitation
- the prefrontal cortex overrides behavior in high-stakes situations

This concept is foundational in:
- reinforcement learning
- robotics
- recommendation systems
- autonomous agents

---

## System 1 vs System 2 Thinking

The coursework explored Daniel Kahneman’s:
- System 1
- System 2

decision framework. :contentReference[oaicite:14]{index=14}

### System 1
Fast:
- intuitive
- automatic
- emotional
- pattern-based

### System 2
Slow:
- deliberate
- analytical
- logical
- planning-based

The module explained that:
- fast thinking is not inherently bad
- problems occur when fast thinking is used in situations requiring deeper reasoning

This section directly connected to:
- LLM behavior
- chain-of-thought prompting
- AI planning agents
- self-reflection systems

---

## Cognitive Biases

The module explored several major cognitive biases including:
- anchoring
- loss aversion
- confirmation bias
- framing effects
- sunk cost fallacy

:contentReference[oaicite:15]{index=15}

The coursework emphasized that:
- human decisions are not perfectly rational
- heuristics can both help and harm decision quality
- AI systems can inherit biases from training data

This section strongly connected to:
- AI ethics
- fairness
- recommendation systems
- alignment problems

---

## Reinforcement Learning and AlphaGo

One of the strongest AI engineering sections explored:
- reinforcement learning
- temporal difference learning
- actor-critic systems
- AlphaGo

The module explained that AlphaGo combined:
- policy networks
- value networks
- Monte Carlo Tree Search

:contentReference[oaicite:16]{index=16}

This architecture resembled:
- fast pattern recognition
- slow planning
- prefrontal simulation
- biological decision systems

The comparison between:
- brain planning
- Monte Carlo Tree Search
- reinforcement learning

was one of the most important concepts in the module.

---

## Autonomous AI Agents

The module introduced the autonomous agent loop:

- PERCEIVE
- REASON
- DECIDE
- ACT
- LEARN

:contentReference[oaicite:17]{index=17}

The coursework explained how modern AI agents combine:
- memory
- tools
- reasoning
- planning
- feedback loops
- self-correction

This section connected strongly to:
- AI assistants
- robotics
- autonomous systems
- LLM agents
- AI copilots

---

## AI Safety and Alignment

The module concluded by discussing:
- AI alignment
- autonomous decision failures
- reward hacking
- safety problems
- unintended optimization behavior

The coursework emphasized the importance of:
- trustworthy AI
- monitoring
- human oversight
- ethical decision systems

This connected directly to:
- autonomous vehicles
- robotics
- generative AI
- AI governance

---

## Skills Developed

- Reinforcement learning understanding
- Autonomous agent architecture analysis
- AI planning systems
- Decision neuroscience interpretation
- AI safety reasoning
- Cognitive bias analysis
- AI alignment concepts
- Monte Carlo Tree Search understanding
- Decision threshold analysis
- AI reasoning system interpretation
- System 1 vs System 2 AI understanding

---

## Final Project Connection

This module strongly supported the course Final Project because it connected:
- biological intelligence
- autonomous systems
- reinforcement learning
- AI reasoning
- decision architectures
- planning systems
- autonomous agents

The concepts from this module directly apply to:
- robotics
- AI assistants
- agent frameworks
- reinforcement learning systems
- LLM reasoning systems
- autonomous AI agents

---

## Reflection

This module was one of the strongest connections between neuroscience and modern artificial intelligence systems. It showed that many AI architectures solve the same computational problems the brain solves:
- selecting actions
- evaluating rewards
- suppressing competing behaviors
- balancing exploration and exploitation
- accumulating evidence
- planning future actions

The most important insight for me was understanding how reinforcement learning closely parallels dopamine reward systems and how autonomous agents resemble biological decision loops.

The System 1 vs System 2 section also helped me better understand:
- why large language models sometimes fail
- why planning agents are important
- why reasoning frameworks like chain-of-thought improve AI performance

Overall, this module greatly expanded my understanding of:
- AI agents
- autonomous systems
- reinforcement learning
- neuroscience-inspired AI
- decision architectures
- AI safety
- AGI research
