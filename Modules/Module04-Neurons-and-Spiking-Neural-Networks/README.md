# Module 04 – Neurons & Spiking Neural Networks

## Overview

This module focused on Spiking Neural Networks (SNNs), neuromorphic computing, and biologically inspired neural computation. The coursework expanded on previous neuron modeling concepts by connecting individual neurons into temporal spiking networks capable of energy-efficient computation and real-time processing.

The module explored the evolution of neural networks from binary perceptrons to deep learning systems and finally to third-generation spiking neural networks.

---

## Topics Covered

- Spiking Neural Networks (SNNs)
- Leaky Integrate-and-Fire (LIF) neurons
- Temporal neural computation
- Spike encoding methods
- Rate coding
- Temporal coding
- Surrogate gradients
- Backpropagation Through Time (BPTT)
- snnTorch
- Neuromorphic computing
- Event-driven processing
- Energy-efficient AI
- Intel Loihi 2
- Neuromorphic hardware
- Brain-inspired computing

---

## Files Included

### Assignment
- A04_Eduardo_CabreraLopez_ITAI4374.pdf

### Python Lab
- L04_Eduardo_CabreraLopez_ITAI4374.ipynb

### Lab Guides
- Module_04_Python_Lab_Guide.pdf
- Module_04_Wolfram_Assignment_Guide.pdf

### Module Booklet
- ITAI 4374 Module 04 Booklet.pdf

### Research & Supporting Resources
- Neuromorphic Hardware Solves Complex Math Efficiently.pdf
- Spiking Neural Networks The Future of Brain-Inspired Computing.pdf
- Neuromorphic computing.pdf

---

## Key Concepts Learned

This module introduced the third generation of neural networks: Spiking Neural Networks (SNNs). Unlike traditional artificial neural networks that process continuous values, SNNs communicate using discrete spikes over time, closely resembling biological neural systems.

I learned how neurons integrate incoming signals, accumulate membrane potential, fire spikes when thresholds are reached, and reset after firing. The Leaky Integrate-and-Fire (LIF) model demonstrated how temporal neural dynamics can be mathematically simulated.

One of the most important concepts in this module was understanding how time becomes part of computation in SNNs. Unlike conventional deep learning systems that process static snapshots, spiking neurons process information continuously over time. :contentReference[oaicite:1]{index=1}

---

## The Three Generations of Neural Networks

### First Generation
- Binary threshold units
- Perceptrons
- Simple on/off outputs

### Second Generation
- Deep learning networks
- Continuous activation functions
- Backpropagation
- CNNs and Transformers

### Third Generation
- Spiking Neural Networks
- Temporal computation
- Event-driven processing
- Energy-efficient architectures

This progression demonstrated how modern AI is moving closer toward biologically realistic computation systems.

---

## Spiking Neural Networks

The module explored how SNNs differ fundamentally from traditional artificial neural networks.

### Key Characteristics
- Temporal spike processing
- Sparse computation
- Event-driven activation
- Membrane potential dynamics
- Energy-efficient inference

### Advantages of SNNs
- Lower power consumption
- Faster real-time processing
- Better temporal data handling
- Closer biological realism
- Efficient edge AI deployment

I learned that SNNs are particularly useful for robotics, autonomous systems, smart sensors, neuromorphic vision, and edge AI devices. :contentReference[oaicite:2]{index=2}

---

## LIF Neuron Simulation

The Python and Wolfram assignments focused heavily on implementing and analyzing Leaky Integrate-and-Fire neurons.

The simulations demonstrated:
- Membrane potential accumulation
- Voltage leakage
- Spike threshold detection
- Spike resets
- Current injection effects
- Temporal neural behavior

The interactive dashboards allowed experimentation with:
- Threshold voltages
- Input current
- Membrane time constants
- Spike frequency

This helped me understand how biological neurons process information dynamically over time instead of instantaneously.

:contentReference[oaicite:3]{index=3}
:contentReference[oaicite:4]{index=4}
:contentReference[oaicite:5]{index=5}

---

## Neuromorphic Computing

One of the most exciting topics in this module was neuromorphic computing, which involves designing hardware systems inspired by biological brains.

The module explored:
- Intel Loihi 2
- BrainScaleS
- SpiNNaker
- Neuromorphic chips
- Event-driven hardware
- Sparse neural computation

I learned how neuromorphic systems can dramatically reduce energy consumption compared to conventional GPUs while maintaining real-time AI performance. :contentReference[oaicite:6]{index=6}

---

## Research Insights

The research papers demonstrated how SNNs are becoming important for:
- Edge AI
- Robotics
- Smart sensors
- Autonomous systems
- Brain-computer interfaces
- Low-power AI devices

One major insight was that spiking neural networks process information asynchronously using spike events instead of dense matrix multiplication, making them significantly more energy efficient than traditional deep learning systems. :contentReference[oaicite:7]{index=7}

---

## Skills Developed

- Spiking neural network concepts
- Temporal neural computation
- LIF neuron modeling
- Python neuron simulations
- Wolfram computational modeling
- Neuromorphic computing knowledge
- Brain-inspired AI understanding
- Computational neuroscience
- Event-driven AI systems
- Scientific research analysis

---

## Challenges

One challenge was understanding how spikes encode information differently from traditional numerical neural networks. Temporal processing introduced a completely different computational perspective compared to standard deep learning systems.

Another challenge was understanding surrogate gradients and how spiking neural networks can still be trained despite spike functions being non-differentiable.

---

## Reflection

This module completely changed my understanding of artificial intelligence and neural computation. Before this module, I mainly associated AI with deep learning and GPUs. Studying spiking neural networks and neuromorphic computing showed me that the future of AI may move toward more biologically realistic and energy-efficient systems.

I also learned how neuroscience continues to influence the future of AI hardware and algorithms. The integration of computational neuroscience, edge AI, robotics, and neuromorphic engineering demonstrated how interdisciplinary modern AI research has become.

This module strengthened my interest in brain-inspired AI systems, neuromorphic computing, and advanced AI architectures.
